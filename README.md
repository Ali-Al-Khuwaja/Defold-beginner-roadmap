> [!NOTE]
> You do not need to understand everything at once. This roadmap is meant to be revisited multiple times as you learn.
>
> If something doesn’t click yet, that’s expected. Skip it and come back later .
>
>it's important that you realize the existence of these resources while doing the tutorials so you know where you should search .
 
Roadmap v1.2
## Welcome to Defold


>[!TIP]
>If you're new to programming and game development, I recommend starting with the official Defold [tutorials](https://defold.com/tutorials/) only after at least finishing reading the four [core concepts](https://defold.com/manuals/building-blocks/) of Defold. These tutorials will give you a sense of self-development and help you get started with the basics, at least that's what I felt.



Here's a roadmap for learning Defold, made for beginners:

**Phase 1: Foundations**

- **Install Defold:** Download and install the Defold editor from the official website [here](https://defold.com/download/).
- **Editor Basics:**
  - Familiarize yourself with the [editor interface](https://defold.com/manuals/editor/): project view, scene editor, properties panel, console, it's very minimal and easy to understand.
- **Learn the four core concepts of Defold:**
> For now, focus on what exists in Defold, don't try to master just yet.
  - Learn about [the building blocks of Defold](https://defold.com/manuals/building-blocks/), game objects, components and collections.
  - Learn about [Addressing](https://defold.com/manuals/addressing/), Code that controls a running game must be able to reach every object and component to manipulate what the player sees and hears, and Defold’s addressing mechanism makes this possible.
  - Learn about [message passing](https://defold.com/manuals/message-passing/), message passing is a mechanism for Defold game objects to communicate with each other.
  - Learn about [application lifecycle](https://defold.com/manuals/application-lifecycle/).

- **Explore the Defold Manual:**
  - skim over the Defold [manuals](https://defold.com/manuals/introduction/) to get a better understanding of the engine and its features.


> You can move on from Phase 1 when:
> - You know what game objects, components, and collections are
> - You understand that objects communicate using messages
> - You don’t fully understand everything — and that’s okay 😉

**Phase 2: Scripting and Game Logic**

- **Lua Scripting Basics:**
  - Learn [enough Lua](https://defold.com/manuals/lua/) to read and slightly modify Defold scripts (not to master Lua): variables, data types, operators, control flow (if statements, loops), functions, there you will be given all the resources you will ever need to learn Lua.

  > Beginner habit:
  > - Use `print()` often to see what your code is doing
  > - Errors are normal and expected
  > - Reading error messages is part of learning

  - Understand how to attach [scripts](https://defold.com/manuals/script/) to game objects and use the `init()`, `update()`, and `on_message()` functions.
- **Basic Game Mechanics (input → logic → result):**
  - Implement movement using [keyboard](https://defold.com/manuals/input-key-and-text/) or [mouse input](https://defold.com/manuals/input-mouse-and-touch/).
  - Create simple [collision detection](https://defold.com/examples/physics/dynamic/) between game objects.
- **Example Projects:** Start with very simple game ideas:
  - "Hello World" with interactive elements (e.g., a button that changes color when clicked).
  - A simple "dodge the falling objects" game or just do a tutorial like snake.

**Phase 3: Intermediate Concepts**

- **Collections and Factories:**
  - Learn how to use collections to organize your game objects.
  - Understand how to use [factories](https://defold.com/manuals/collection-factory/) to create instances of game objects at runtime.
- **Animation:**
  - Learn how to create and use sprite [animations](https://defold.com/manuals/animation/).
  - Implement animation based on game events (e.g., walking animation when moving).
- **User Interface (UI):**
  - Learn how to create and manage [UI elements](https://defold.com/manuals/gui/) (buttons, text, images).
  - Implement basic UI interactions.

  > Tip: UI (GUI scripts) should usually not control gameplay directly.

- **Sound and Music:**
  - Learn how to [add sound effects](https://defold.com/manuals/sound/) and background music to your game.
- **More Complex Projects:**
  - A simple platformer with basic movement, jumping, and collision, there is an example game already made if you need.
  - A top-down shooter with basic enemy AI.


**Phase 4: Advanced Topics and Polish (Ongoing)**
> You do not need this phase to make and publish simple games.

- **Physics:** Dive deeper into the [physics](https://defold.com/manuals/physics/) engine for more realistic movement and interactions.
- **Advanced Scripting:** Learn more advanced Lua techniques, such as object-oriented programming.
- **Shaders:** [Explore shaders](https://defold.com/manuals/shader/) to create visual effects.
- **Networking:** If you're interested in multiplayer games, learn [about networking ](https://defold.com/manuals/networking/)concepts and Defold's networking capabilities.
- **Optimization:** Learn how to [optimize your game](https://defold.com/manuals/optimization/) for performance.
- **Publishing:** Learn how to build and publish your game to different platforms, it's all in the manual.
- **Community and Resources:**
  - Engage with the Defold community on the forum and Discord.
  - Explore community-created extensions and libraries.
  - Continue learning through tutorials, documentation, and example projects.


**Tips:**

- **Start small:** Don't try to create a complex game right away. Start with small, manageable projects and gradually increase the complexity.
- **Focus on understanding the fundamentals:** Make sure you have a solid understanding of the basic concepts before moving on to more advanced topics.
- **Don't be afraid to ask for help:** [The community forum](https://forum.defold.com/) is very helpful and welcoming to beginners, also check the discord server.
- **Official examples:** Work through the [examples](https://defold.com/examples/), These are a great starting point and cover the basics effectively.

> This roadmap is not a checklist.
> It’s a map you return to as your understanding grows.
> It's okay to use AI for explaining concepts
