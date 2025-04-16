## Rocksky CLI

🎧 The official command-line interface for [Rocksky](https://rocksky.app) — a modern, decentralized music tracking and discovery platform built on the AT Protocol.

## Features
- 🔐 Authenticate with your Rocksky account using OAuth
- 🎵 View your currently playing track
- 📈 See your recent scrobbles
- 📤 Manually scrobble tracks
- 🛠️ Useful developer tools for integrating Rocksky into your workflows

## Run in development
To run the CLI in development mode, install the dependencies:

```bash
bun install
```

Then, run the CLI with:

```bash
bun run dev --help
```


## Usage

```bash
rocksky <command> [options]
```

## Available Commands

`login` - Initiates a browser-based OAuth login flow and saves your access token securely on your machine.

```bash
rocksky login
```

`nowplaying` - Displays the currently playing track on your/other Rocksky account.

```bash
rocksky nowplaying
```

`scrobbles` - Lists all recently scrobbled tracks.

```bash
rocksky scrobbles
```

`search` - Searches for tracks, albums, artists or Rocksky users.

```bash
rocksky search <query>
```