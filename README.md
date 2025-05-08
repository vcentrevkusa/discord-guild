# New working code for creating Discord guild servers  

Before running the script, ensure you have completed the following steps:

Disable 2FA: The script needs 2FA disabled to automatically delete temporary servers without requiring confirmation prompts. Re-enable 2FA after you finish using the script.
Install Vencord: This script relies on functions exposed by the Vencord client modification. Download and install it from the official source.
Enable Vencord Plugin: Open Discord Settings, go to the Vencord "Plugins" tab, find and enable the ConsoleShortcuts plugin. This plugin exposes useful library functions (like findByProps) to the developer console, which are necessary for this script to work.
Restart Discord Client: Close and reopen Discord completely to ensure Vencord and the plugin are loaded correctly.
Create One Server Manually (Required): Before running the script make sure to create a single server through the normal Discord interface first. It's a required step.

## Instructions

- Open Developer Console: Use the standard browser/Electron method to open the developer console (usually Ctrl+Shift+I on Windows/Linux or Cmd+Option+I on Mac, or sometimes F12).
- Allow Pasting (If Prompted): The console might require you to explicitly type allow pasting before accepting pasted code.
- Paste and Run Code: Copy the entire JavaScript code block below, paste it into the console, and press Enter.
- Remember to re-enable 2FA on your account once the script has found a server or you decide to stop it.

## Troubleshooting
Why do I get the Uncaught TypeError: Cannot read properties of null (reading 'createGuildFromTemplate') error?
1.1. You need to manually create a new server before running the script; otherwise, the script won't be able to create a new server. If you ever need to run this script again, you'll need to repeat this step.

Why do I get the Uncaught ReferenceError: findByProps is not defined error?
2.1. You need to install Vencord and enable the ConsoleShortcuts plugin (not the ConsoleJanitor one!). After that, restart your client, manually create a server, and then run the script.

How can I remove the "Hold Up!" messages from the console?
3.1. You can use the ConsoleJanitor plugin to eliminate messages like these, but it's not a necessary step.

## Price / Script - 20$ 

DS: aura.meta

![image](https://github.com/user-attachments/assets/e72110ab-1734-4cc5-92b6-287de68c2708)
