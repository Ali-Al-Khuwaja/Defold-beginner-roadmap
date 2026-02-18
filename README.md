# New Changes: Build First, Understand Later. V 1.4.1

What's new?
1. Road-map freeze .
2. Build First, Understand Later.

I noticed that the road-map is boring and felt more like work than a hobby, I just couldn't continue studying it.
Maybe I was too reliant on AI helping me form a road-map, So I decided to stop it there and start adding the human part in.
I want to refactor it to a Road-map that goes like **"I want to do X then ask how to do X and how it works"** instead of **"Here learn X Y Z  because you will need it in the feature"**

What I'm saying is that the "New Changes" will be project oriented first and theory second, I don't really have experience in creating such projects so I will use AI to help me, it will also take a lot of time to make 🙂.

Final note:
I think any new AI model can generate such road-map in seconds, maybe not in one prompt but it can surly achieve something similar of what I had cooking .

Freezing the current map is the only choice available, I'm building the Road-map and applying it at the same tame, it will not be a smooth ride.

---

 
Roadmap v1.4.1
## Welcome to Defold


Here's a roadmap for learning Defold, made for beginners:

> [!IMPORTANT]
> While following this roadmap, your goal is not to write perfect code.
> Your goal is to understand *why things work* and *why they break*.

---

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
  - While reading, focus on recognizing names and ideas, not memorizing details.


> You can move on from Phase 1 when:
> - You know what game objects, components, and collections are
> - You understand that objects communicate using messages
> - You don’t fully understand everything — and that’s okay 😉

---

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
  > When following a tutorial:
  > - Pause and predict what the code will do before running it
  > - Change small things (values, names, speeds) to see what breaks
  > - If something breaks, that’s progress

---

## Common Beginner Traps (Read when you feel stuck)

- **“I must understand everything before moving on”**
  - You don’t. Recognition comes before understanding.

- **“My code is messy, so I’m doing it wrong”**
  - Messy code is normal at this stage. Clarity comes later.

- **“This tutorial makes sense, but I can’t do it alone”**
  - That’s expected. Tutorials teach exposure, not mastery.

- **“I should restart from zero”**
  - Only restart if you know *why*. Otherwise, continue.

- **“Everyone else gets this faster than me”**
  - You’re only seeing results, not confusion.

> If you’re stuck for more than 30–60 minutes:
> - Take a short break
> - Ask a specific question
> - Or move on and come back later

--- 

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

--- 

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

---


**Tips:**

- **Start small:** Don't try to create a complex game right away. Start with small, manageable projects and gradually increase the complexity.
- **Focus on understanding the fundamentals:** Make sure you have a solid understanding of the basic concepts before moving on to more advanced topics.
- **Don't be afraid to ask for help:** [The community forum](https://forum.defold.com/) is very helpful and welcoming to beginners, also check the discord server.
- **Official examples:** Work through the [examples](https://defold.com/examples/), These are a great starting point and cover the basics effectively.


> [!NOTE]
> This roadmap is not a checklist.
> It’s a map you return to as your understanding grows.
>
> You are learning correctly if:
> - You feel confused but curious
> - You often say “oh, that’s why”
> - You break things by experimenting
> - You don’t remember everything, but recognize it later
>
> It's okay to use AI for explaining concepts

This Roadmap is being cooked on calm fire, by me and ChatGPT in a controlled, gradual way.
I will keep improving weak points every now and then, every line here is been discussed with psychological effect in mind.

A Roadmap is important for the confused newcomers like myself, I aim to :
- Reduce pressure on the learning journey 
- Clarify when to move on
- Normalize confusion
- Add enough direction

This is possible thanks to the defold manual and ChatGPT, I'm myself, also a confused newcomer who haven’t found a roadmap, that's why I decided to make it myself with the help of the internet🙂. 


