## Introduction

Meet GitDiaryBot, a Telegram bot. It helps writing a plain text diary synchronized by Git.
When you send a message to GitDiaryBot, it:

1. Pulls your Git repository.
2. Appends the message to the end of a diary file.
3. Commits and pushes new version back to your Git repository.

## Who wants it?

If you are journaling in a [simple text file](https://jeffhuang.com/productivity_text_file/),
Telegram can make it easier to quickly add new records.
Optionally, you can configure Google API token, to transcribe voice message and add addresses to location messages.

## Install GitDiaryBot

1. Add [GitDiaryBot](https://t.me/GitDiaryBot) to your Telegram account.
2. If your Diary is hosted on GitHub in private repository, add GitDiaryBot as collaborator
   to the repository in Settings > Manage Access > Invite collaborators.
3. Send a message to the bot following this template:
   ```/start git@github.com:peterdemin/diary.git```
