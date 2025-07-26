# Notification Sounds for Claude Code on iOS

**Before audio cues**
- Leave Claude hanging when it needs input
- Incessantly toggle back and forth between your work and Claude's progress

**After audio cues**
- Never leave Claude hanging for any longer than you want
- Shift focus to your parallel work and get notified when you're needed

## How to set it up

1. Open your Claude directory
  ```bash
  cd ~/.claude
  ```
2. If you have a ```scripts/``` directory, ```cd``` into it; otherwise, create one.
3. Add the 2 ```.sh``` files from this repo. (There's a 7 second delay for the "Claude needs input" sound, which is unavoidable; I've tried workarounds to no avail)
4. Update your ```settings.json``` as shown in the ```.json``` file in this repo.
5. Start a fresh Claude session and enjoy audio notifications.

## Troubleshooting

If you don't hear sounds when it needs your input or when it prompts you with its prompt box, just ask it to help you figure it out...

There might be some other settings to change in your IDE and/or system settings.
