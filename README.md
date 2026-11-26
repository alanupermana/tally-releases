<p align="center">
  <img src="icon.png" width="96" height="96" alt="Tally icon">
</p>

<h1 align="center">Tally</h1>

<p align="center">Your daily worklog for Taiga, written for you.</p>

Tally is a macOS app that turns your day into Taiga worklog tasks. Type it, pull it from your work tools, or let AI write it. You check every row before anything is sent.

- **Quick Log and Text Log**: log tasks by hand, no AI needed.
- **Write With AI**: describe your day in your own words and get tasks with times and tags.
- **Pull Activity**: read your Claude Code and Codex sessions, GitLab, GitHub and Figma activity.
- **Review**: every row is checked by you before it goes to Taiga.
- **Scheduled Drafts**: optional. Tally prepares the day's draft after work and waits for your review.

> Coming soon: a web version and Windows.

## Install

**Requirements:** macOS 11 Big Sur or later on Apple Silicon (M1 or newer), and a Taiga account.

1. Download the latest `Tally_x.y.z_aarch64.dmg` from [Releases](../../releases/latest), or from [tally-site-two.vercel.app](https://tally-site-two.vercel.app).
2. Open the file and drag **Tally** into **Applications**.
3. The first time, right-click **Tally** in Applications and choose **Open**, then **Open** again. Tally is not notarized by Apple yet, so macOS asks once.
4. Follow the setup: connect Taiga, choose your projects and your work hours. A short tour shows you around.

### Keychain prompts

Tally keeps your tokens in the macOS Keychain, never in a file. macOS asks once for each one, for example "Tally Taiga token". Choose **Always Allow** so it does not ask again.

### Update

Download the new `.dmg`, drag Tally into Applications and choose **Replace**. Your settings and notes stay.

### Uninstall

Drag Tally from Applications to the Trash. To remove your data too, delete `~/Library/Application Support/id.tally.app` and the "Tally" items in Keychain Access.

## Where your logs go

Tally keeps one user story per Taiga project per month, named `Activities {your full name} - {Month} {Year}`, and every log becomes a task inside it. The name format is fixed.

## Privacy

Nothing goes to a Tally server: there is none. Your text and activity go only to the AI provider you choose in Settings, and only when you press Write to Review (or turn on Scheduled Drafts). Tasks go to Taiga only when you press Send.

## Help

Open **Help** in the app, or choose **Need Help?** at the bottom of the sidebar. You can also write to alanupermana@gmail.com.

## License

Copyright (c) 2026 Alanu Dinasti Permana. All rights reserved.

Tally is free to download and use. It is not open source. You may not copy, modify, redistribute or reverse engineer it. See [LICENSE](LICENSE). Want to contribute or build on it? See [CONTRIBUTING.md](CONTRIBUTING.md).
