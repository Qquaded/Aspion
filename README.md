# Aspion Anti-Cheat

Aspion is a powerful and efficient anti-cheat system designed for Roblox, focused on maintaining game integrity by preventing malicious activities through server-client verification.

## Features

- **Server-Side Management**: The anti-cheat operations are executed on the server, ensuring secure management of the client-side script.
- **Client Script Cloning**: Aspion clones the client anti-cheat script from the server to the player's GUI.
- **Automatic Cleanup**: After the client script is cloned, Aspion immediately destroys the original script, minimizing the chance of manipulation or bypass.

## How It Works

1. **Server Execution**: Aspion is placed in `ServerScriptService`, where it securely handles the anti-cheat operations.
2. **Client Cloning**: The server clones the anti-cheat script and places it in the player's GUI.
3. **Script Destruction**: After cloning, the original anti-cheat script is destroyed to prevent tampering.

## Installation

To integrate Aspion into your Roblox game, follow these steps:

1. **Clone the Repository**: Download or clone the Aspion repository to your Roblox Studio project.
2. **Place in ServerScriptService**: Place the Aspion script in the `ServerScriptService` within your game's hierarchy.
3. **Configure Client Script**: Customize the client-side script if necessary, ensuring it aligns with your game's specific anti-cheat needs.
4. **Deploy the System**: Test and deploy Aspion in your game environment.

## Updates

To get the latest updates in aspion:
1. **Find Package link**: Find the package link in the model/script.
2. **Set property**: Set the package link property AutoUpdate to *true*.
