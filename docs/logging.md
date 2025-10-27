---
sidebar_position: 3
---

# Configuring Logging

This guide explains how to enable additional logging for the Gameplay Messaging System to help with debugging and monitoring gameplay events in your Unreal Engine project.

## Enable Verbose Logging

To enable detailed logging for the Gameplay Messaging System, you need to modify your project's configuration file (`DefaultEngine.ini`). This will allow the system to output verbose logs, which can be useful for tracking message triggers, payloads, and other system activities.

1. **Locate the Configuration File**:
   - Navigate to your project’s `Config` folder, typically found at `<YourProjectRoot>/Config/`.
   - Open the `DefaultEngine.ini` file in a text editor.

2. **Add Logging Configuration**:
   - Add the following lines to the `DefaultEngine.ini` file under the appropriate section (or at the end if no specific section exists):
     ```ini
     [Core.Log]
     LogGameplayMessageSubsystem=Verbose