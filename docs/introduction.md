---
sidebar_position: 1
slug: /
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Gameplay Messaging System Documentation

The Gameplay Messaging System is a powerful and flexible tool for Unreal Engine that enables seamless communication across your project. It allows you to broadcast and receive messages without the need for direct references, object casting, or complex dependencies, making it ideal for modular and scalable gameplay systems.

## Features

- **Decoupled Communication**: Broadcast and receive messages anywhere in your Unreal Engine project without requiring direct references, casting, or object dependencies.
- **Versatile Integration**: Connect Blueprints, Actors, Components, and Subsystems effortlessly through project-wide communication channels.
- **User-Friendly**: Designed to be accessible for both game designers and programmers, with full Blueprint exposure and intuitive workflows.

## Core Functionality

- **Global Messaging Network**: Send and receive gameplay events from any part of your project, eliminating the need for direct references or complex setup.
- **Lightweight & Fast**: Engineered for performance, the system introduces near-zero overhead, ensuring it integrates smoothly into your game logic.
- **Blueprint-Accessible**: All functionality is fully exposed through Blueprints, enabling designers to implement messaging without writing code.

## Messaging System Highlights

- 🧩 **Message Registration**  
  Register custom message types and subscribe to them from any Blueprint or C++ class, enabling flexible event handling.
  
- 📬 **Global Message Dispatching**  
  Broadcast messages to all listeners across the project, ensuring efficient communication without direct connections.

- 🔄 **Parameter Support**  
  Include payloads (structs, values, enums, etc.) with messages to share data seamlessly between systems.

- 🎮 **Editor & Runtime Safe**  
  Operates reliably in both Play-In-Editor (PIE) sessions and packaged builds, making it suitable for gameplay, UI, and debugging.

- 🧠 **Event-Driven Architecture**  
  Replace tightly coupled references, casts, and dependency chains with a clean, modular event-based system.

## Use Cases

The Gameplay Messaging System is versatile and can be applied to a wide range of scenarios, including:

- **Replacing Tightly Coupled Event Dispatchers**: Simplify your project by using global messages instead of managing complex event dispatcher chains.
- **Global Announcements**: Trigger events like `MatchStarted`, `PlayerDied`, or `WeatherChanged` to notify relevant systems or actors.
- **UI Notifications or HUD Updates**: Send messages to update user interfaces, such as health bars, score displays, or quest logs.
- **Subsystem Communication**: Facilitate interaction between game subsystems or managers (e.g., inventory, audio, or AI systems).
- **Debug and Developer Tools**: Use the system to log events or trigger debug actions during development and testing.

The Gameplay Messaging System empowers you to create modular, scalable, and efficient communication workflows, streamlining development and enhancing your project’s flexibility.