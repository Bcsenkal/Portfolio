# Portfolio
Highlights of my professional experience in Game Development industry

### SWAT Tactical Shooter 

https://play.google.com/store/apps/details?id=com.RocinanteGames.SwatTacticalShooter&hl=en 

An immersive tactical shooter that places players in the role of a highly trained SWAT officer. The game emphasizes strategic planning, precision, and quick decision-making as players engage in high-stakes operations to neutralize threats and rescue hostages. Features include realistic environments, diverse mission scenarios, and a variety of weapons and equipment to enhance the tactical experience.

### Money Color Sort 

https://play.google.com/store/apps/details?id=com.RocinanteGames.MoneyColorSort&hl=en&gl=US 

A visually engaging puzzle game focused on sorting and organizing currency by color and denomination. The game promotes logical thinking and accuracy, offering a blend of fun and cognitive challenge. 

### Park Mania Jam 

https://play.google.com/store/apps/details?id=com.RocinanteGames.ParkManiaJam&hl=en 

A challenging jam game that combines parking tangle with soda can delivering. 

### Juice Jam 

https://play.google.com/store/apps/details?id=com.RocinanteGames.JuiceSortJam&hl=en 

A vibrant and fast-paced puzzle game where players solve triple-match challenges by combining colorful fruits. Designed with levels of increasing complexity, it emphasizes engaging visuals and accessible gameplay. 

### Bolts Away Screw Puzzle 

https://play.google.com/store/apps/details?id=com.RocinanteGames.BoltsAway&hl=en 

A logic-based puzzle game where players unscrew and match bolts to solve mechanical challenges. The gameplay focuses on problem-solving, spatial reasoning, and an intuitive interface. 

### Bolts Jam 

https://play.google.com/store/apps/details?id=com.RocinanteGames.BoltsJam&hl=en 

An engaging puzzle game centered around sorting and matching bolts of various types. It encourages players to think critically and strategically to complete each level. 

### Monster Hunter: Last Stand 

https://play.google.com/store/apps/details?id=com.RocinanteGames.MonsterHunter&hl=en 

An action-packed game where players take on the role of a monster hunter defending humanity. With a focus on combat strategy and weapon customization, players battle against challenging creatures to ensure survival.

### Candy Clash - Sort & Merge

https://play.google.com/store/apps/details?id=com.RocinanteGames.CandyClash

A level and goal based suika game, like Fruit Clash from SayGames.

### Aqua Party

https://play.google.com/store/apps/details?id=com.anotherworld.aquaparty

Aqua Party is a grid-based mobile sorting puzzle game in which players move color-coded groups and life buoys through a crowded board into capacity-limited trays. The gameplay combines spatial planning, path management, matching mechanics, and dynamic obstacles such as dispensers, hidden entities, and inflatable objects.
As the primary gameplay and tools programmer, I developed the game’s movement architecture, including group detection, footprint-aware A* pathfinding, coordinated agent movement, collision handling, and crowd simulation. I also implemented the tray and queue systems, object pooling, tutorials, revive mechanics, visual themes, audio, and gameplay effects.
A major part of the project was creating XLevelTool, a reusable Unity level-production framework. It provides grid, spline, and freeform editing; property-driven level data; runtime baking; scene visualization; validation rules; and automated simulations that evaluate level solvability and approximate player behavior. This allowed gameplay content to be created, inspected, and tested directly inside the Unity Editor.

### Arrow Branch

https://play.google.com/store/apps/details?id=com.anotherworld.arrowbranch&hl=en

Arrow Branches is a spatial mobile puzzle game in which players clear a network of intertwined arrows in the correct order. Each arrow can move only in its facing direction and must have an unobstructed path. Branch relationships, collisions, frozen arrows, limited lives, and timed or move-based objectives add further layers of planning.
As a primary gameplay and tools programmer, I developed the central arrow architecture: spline-based movement, hierarchical branch dependencies, collision and blocking rules, input prioritization, camera controls, level-state management, and power-ups such as hints, path previews, and arrow removal.
I also created a procedural ribbon-mesh system for rendering smooth curved arrows. It supports adaptive curve subdivision, configurable smoothing, rounded arrowheads and tails, pooled runtime meshes, and shader-driven effects for blocked, frozen, highlighted, spawning, and unfreezing states. A spatial-hashing system accelerates collision checks between complex spline shapes.
For content production, I expanded the project’s Unity level-authoring tools with spline editing, live arrow-width previews, property-driven level data, tutorial authoring, runtime baking, and a dedicated validator for detecting collisions, invalid branches, and unsolvable configurations.

### Cut Out

https://play.google.com/store/apps/details?id=com.anotherworld.islandharvest

Island Harvest is a grid-based mobile puzzle game in which players guide a saw across an island, cutting connections to detach sections of colored blocks. Detached pieces transform into collectibles, travel through a capacity-limited tray, and fill matching objectives. Players must plan their cuts carefully while navigating frozen regions, locked chains, keys, isolated sub-islands, and restricted traversal paths.
As the primary gameplay and tools programmer, I developed the central gameplay architecture. This included swipe recognition, node-to-node saw movement, graph-based connectivity analysis, cut resolution, detached-component detection, collectible routing, tray management, objective matching, and win/fail evaluation.
The project contains a detailed visual pipeline for making each action feel physical and responsive. I implemented procedural cut masks, progressive surface displacement, impact craters, morphable collectible meshes, island silhouettes, pooled particles, animation sequencing, sound, and haptic feedback. Collectibles can move through multiple states—from their original grid position to overflow storage, the tray, and finally their matching objective.
I also developed interconnected mechanics for frozen areas, keys and chains, and secondary islands. The sub-island system resolves authored spline routes, generates channel-shaped path meshes, controls saw traversal and impact sequences, and integrates detached sections back into the main collection flow.
For content production, I expanded the custom Unity level editor with multi-layer grid, spline, and freeform data; visual previews; level baking; validation rules; tutorial authoring; reusable themes; and designer-configurable gameplay settings.

