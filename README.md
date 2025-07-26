# Notification Sounds for Claude Code on iOS

While Claude's doing it's thing, I'll often be on another screen doing parallel work.

Before audio cues, I'd leave Claude hanging when it needs input or I'd incessantly toggle back and forth between my work and Claude's progress.

After audio cues, I can shift focus to my work until Claude lets me know I'm needed. Which has been a much better workflow.

## How to set it up

1. Open your Claude directory
  ```bash
  cd ~/.claude
  ```
2. If you have a ```scripts/``` directory, ```cd``` into it; otherwise, create one.
3. Add the 2 ```.sh``` files from this repo.
4. Update your ```settings.json``` as shown in the ```.json``` file in this repo.
5. Start a fresh Claude session and enjoy audio notifications.

## Troubleshooting

If you don't hear sounds when it needs your input or when it prompts you with its prompt box, just ask it to help you figure it out...

There might be some other settings to change in your IDE and/or system settings.
