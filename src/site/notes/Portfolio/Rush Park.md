---
{"dg-publish":true,"permalink":"/portfolio/rush-park/","tags":["portfolio"],"dg-note-properties":{"tags":["portfolio"]}}
---

Rush Park is a 2v2 character-based sports game about hitting a rapidly accelerating ball into the opposing team’s goal. Rather than using a conventional scoring system, each goal moves all characters to a new stage (either left or right) creating a tug of war dynamic. Each stage has different effects that the teams can use to their advantage. This project was done in a custom engine, written from scratch in C++.

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=a0PPfz2scUI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# My Roles
- Writing multiplayer input management with XInput.
- First pass creation of our custom editor, using ImGui for the UI.
- Serialization and Deserialization systems for saving and loading levels build in our level editor.
- Level design for the different stage effects.
- Implementation of the stages through the level editor.

# What I learned
This was my first time working on a multi-discipline project, and it was the biggest project I had done up to that point. Team communication between disciplines, especially in regards to limitations of our custom engine were crucial to our success. We experienced some team difficulties that we had to figure out and push through, which was a good learning experience.

We wanted to make a very fast-paced game with unique playstyles, and we did kind of succeed in one of those. Our game was very fast, and wouldn’t drag on for players. Each of the four playable characters had a different ability that would affect the ball in an interesting way. Due to having only one different action between them though, the characters would feel very similar despite their different stats and very different visuals. I think that sound played a huge role in this shortcoming. We had a lot of issues regarding the sound in our game (that actually hearkens back to some of our team issues) so the sound effects and music were very basic.

The game was a massive UX challenge that we had not accounted for at all. It’s a fast-paced local 2v2 game where each player has a fillable ability bar, a goal to defend, a goal to score into, a rapidly moving ball, 3 other players to watch out for (one of them being a teammate), and the screen changes on goals. Being able to communicate all of this information to each player at the same time was a herculean task. This was definitely our biggest shortcoming in this project and taught us all a lot about planning for UX early on.

