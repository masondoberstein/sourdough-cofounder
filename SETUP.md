# Setup (about 20 minutes, one time)

You'll install four things, then open this project. Mac steps below. Windows notes at the bottom.

## 1. A Claude subscription

Go to claude.ai and sign up for **Pro** or **Max**. Claude Code is included. Max gives a lot more room if you use it every day.

## 2. VS Code

Download from code.visualstudio.com, open the download, drag it into Applications, and open it.

## 3. Git and GitHub

1. Open the **Terminal** app (press Cmd + Space, type Terminal, hit enter).
2. Paste this and hit enter. If a popup asks to install developer tools, click Install:

```
git --version
```

3. Install the GitHub helper so you never have to deal with passwords:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install gh
gh auth login
```

For `gh auth login` pick: GitHub.com, HTTPS, Yes, Login with a web browser. Copy the code it shows, paste it in the browser page that opens.

## 4. Claude Code

Paste this in Terminal:

```
curl -fsSL https://claude.ai/install.sh | bash
```

Close Terminal and open it again so it picks up the new command.

Optional but nice: in VS Code, click the Extensions icon on the left (four squares), search **Claude Code**, and install it.

## 5. Get your copy of this project onto your computer

First make your own copy on GitHub (the **Use this template** button in README.md). Then in Terminal, swap in your GitHub username and repo name:

```
cd ~/Documents
gh repo clone YOUR-USERNAME/my-sourdough-channel
cd my-sourdough-channel
code .
```

(If `code .` doesn't work: in VS Code press Cmd + Shift + P, type "shell command", choose **Install 'code' command in PATH**, then try again.)

## 6. Start your co-founder

In VS Code open the terminal at the bottom (Ctrl + backtick, the key under Esc) and type:

```
claude
```

Log in with your Claude account the first time. Then type:

```
/onboard
```

That's it. From here on, just open the folder in VS Code, type `claude`, and talk to it like a person.

## Optional extras (ask Claude to walk you through any of these)

- **Video editing:** needs Node.js and FFmpeg. Just tell Claude "set up video editing" and it will install them with you.
- **Web research boost:** a Firecrawl account (firecrawl.dev) lets Claude read TikTok and Instagram pages and websites more reliably. Claude works without it.
- **Backing up your work:** at the end of a session say "save and push my work". Your files go to your private GitHub repo.

## Windows

Install VS Code and Git for Windows (git-scm.com), then GitHub CLI from cli.github.com. For Claude Code, open PowerShell and run `irm https://claude.ai/install.ps1 | iex`. Everything else is the same.

## Rule of thumb

Your co-founder never posts, DMs, or emails anyone on its own. It drafts, you post.
