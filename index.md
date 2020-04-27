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
   ```/start git@github.com:username/repository.git```

## Grant Access

GitDiaryBot supports several ways for providing access:

1. For diaries hosted on *GitHub* as private repositories, add GitDiaryBot as a collaborator in *Settings -> Manage Access*.
2. For diaries hosted on *GitLab* as private repositories, invite GitDiaryBot in *Settings -> Members*.
3. For other kinds of hosting platforms, add the following public SSH key:

```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDLHxtY2HyjgdJs/RHQG3vGbDDrxys/P0KMvtEeXrgq3LL2S825XUcX2LFSwiWkqMkM22JBS7dGfuNmWy8rZP0RcH/RUK+tOYO7QelH1xS3cmProTF6pAXoSxJnRsvyS3TtF2LKSBiqY7geHo7GPkaNILKAsw5cgYDkKDRbEgndZRHrD1Bw0/Aixa9P8dWwSY06tyDRoCVfZXEnoX7k82dTtmwpbHf5QmU2DqDn5WqkBNPOtfBQEnMH3qZ3kgBYHWuMgWzbQVyO0Rc7vcS/2CfOaGWV16zLyealVOfmbJnEstn8iHETw2IFjaiupZIezSPYOnyycmEZEMinYYsLIRX2Yt/xUNEZ8oYqci8SRDx+F7TvaX/ff6PvCJdccj0c8eSP4p8u1SckVq6lXvISKgHzHilD1LZpjjPGHg9mrpUH2r0jsfwBQh9Kfy3bxK2DZ7Sk/slyG7u8hNVefF+2eia39sLxhFeJK48aAslL0gOlv5ViUCw0MtjAVzcFOkAXM1M= GitDiaryBot
```
