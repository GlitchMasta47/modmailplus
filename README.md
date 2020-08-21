# ModMail+
A Discord bot that makes it easier for your server members to contact you. Based on Reddit's modmail and Discord Tester's private BugMail bot.

## Why choose this bot?
Sure, there are many other modmail bots available, but many of them have complicated setups, don't allow users to reply on the same thread, or use embeds for everything which, while cool looking, take up more space than necessary and make the experience more complicated. Based on the simplicity of Discord Tester's BugMail, this bot does its job without adding unnecessary steps.

## Why open source?
Hopefully by open-sourcing this bot, I'll be able to inspire better versions of this bot to exist or be able to take pull requests for new features.

## How to self-host
1. Download the repo [as a ZIP](https://github.com/GlitchMasta47/modmailplus/archive/master.zip) or `git clone` to your computer.
2. Run `npm install` to install all dependencies, or `npm install --no-optional` if you want a lighter node_modules
3. Rename `src/core/config.json.example` to `src/core/config.json` and input values as needed
3. You can now use `npm start` or `node .` to start the bot, or use a process manager like pm2 to keep the bot online in the background.

## Contributing
All contributions are welcome, but make sure that your code doesn't have any linter warnings or code errors before making a pull request.

## License
This project uses the MIT License, which is available in the LICENSE file.
