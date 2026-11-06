# Marketing Mini-Game Suite

A collaborative freelance Unity project combining three short games for a client marketing project: match-3, fruit slicing and memory matching, with shared progression and reward interactions. Developed during summer 2023.

[My portfolio](https://haithem-portfolio.vercel.app/)

## My contribution

- Worked on card-game interactions, score and flip-count UI, and game-manager flow.
- Implemented and refined spin-wheel controls, spin-count feedback and checks against overlapping spins.
- Added reward presentation when the wheel finishes spinning.
- Iterated with the client and collaborators on gameplay and presentation.

This suite was co-developed. I did not independently create every mini-game. The repository includes substantial teammate work, including the Ninja Food/Sushi game.

## Design and implementation

The collection links short play sessions to visible score and reward feedback. In the card game, the interface tracks flips and score. The wheel tracks available spins, prevents another spin while one is active, and moves to reward presentation when the wheel stops.

## Explore the code

- [Card-game scripts](Assets/Guessing%20Game): card interaction and game flow.
- [SpinWheel.cs](Assets/Haithem/Media/Spin2Win%20media/SpinWheel.cs): spin state, available spins and rewards.
- [SceneLoader.cs](Assets/Scripts/SceneLoader.cs): shared scene and UI helpers.

## Open the project

1. Clone the repository.
2. Add the root folder in Unity Hub.
3. Use **Unity 2021.3.5f1**, as recorded in `ProjectSettings/ProjectVersion.txt`.
4. Allow packages and assets to import, then inspect the configured scenes in Build Settings.

## Status and next steps

This repository preserves the client-project source. It does not provide a verified public release package. Areas to improve include clearer UI/game-state transitions and testing repeated inputs during spin and reward flows.

## Credits

Collaborative work by Haithem Elhadj and Mohamed Aziz Nabli is recorded in the Git history. Asset and package creators retain their own attribution and licensing terms.
