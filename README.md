# Slackmarks
> Do you wish to store a web page in Slack for personal reference?
Just Press `Cmd + B` / `Ctrl + B`

## How to achieve this?
- ### Set up Slack Bot
  - Let's say your workspace name is "myspace"
  - Head to Slack apps > https://myspace.slack.com/apps
  - Search for `Bots`
  - Click `Add Configuration` and give it a username (say _bookmarks-bot_), purpose, etc.
  - A Bot token starting with `xoxb-` will be generated.

  - Clone this Repo.
  - __Change the Token and channel name__ in `config.js` accordingly.
  - Visit chrome settings & ensure that the Developer mode is turned on in extensions.
  - Click Load unpacked extension.
  - Select the directory.
  - :tada: It's done!

## How to use
- Press `Cmd + B`
- Or Right-click mouse and select `Slack this`
- A _notification_ comes from __bookmarks-bot__ 
- All your bookmarks are saved in __bookmarks-bot__ chat window.
