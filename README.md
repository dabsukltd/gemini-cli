# Phoenix CLI

[![Phoenix CLI](https://img.shields.io/badge/Phoenix-CLI-orange.svg)](https://github.com/phoenix-ignite/phoenix-cli)

![Phoenix CLI Screenshot](./docs/assets/phoenix-screenshot.png)

**Phoenix CLI** - Reborn from memory issues with optimized performance and cross-platform compatibility.

This is an enhanced fork of [Google's Gemini CLI](https://github.com/google-gemini/gemini-cli) with personal fixes and improvements, focusing on:

✨ **Key Improvements:**
- 🚀 **Memory Optimization** - Fixed memory allocation issues for better performance
- 🔧 **Cross-Platform Compatibility** - Enhanced Windows, macOS, and Linux support
- ⚡ **Performance Enhancements** - Streamlined codebase for faster execution
- 🛠️ **Bug Fixes** - Resolved critical issues from the original repository
- 🎯 **Simplified Experience** - Cleaner interface without unnecessary complexity

**Core Features:**
- Query and edit large codebases with improved memory handling
- Generate applications from PDFs or sketches using multimodal AI
- Automate operational tasks with enhanced reliability
- Connect tools and MCP servers with better stability
- Ground queries with integrated search capabilities

## Quickstart

1. **Prerequisites:** Ensure you have [Node.js version 20](https://nodejs.org/en/download) or higher installed.
2. **Clone and Install:**

   ```bash
   git clone https://github.com/phoenix-ignite/phoenix-cli.git
   cd phoenix-cli
   npm install
   npm run build
   ```

3. **Run Phoenix CLI:**

   ```bash
   npm start
   ```

   Or install globally:

   ```bash
   npm install -g .
   phoenix
   ```

4. **Pick a color theme**
5. **Authenticate:** When prompted, sign in with your personal Google account for API access.

You are now ready to use Phoenix CLI!

### Use a Gemini API key:

Phoenix CLI uses the same API authentication as the original Gemini CLI:

1. Generate a key from [Google AI Studio](https://aistudio.google.com/apikey).
2. Set it as an environment variable:

   ```bash
   export GEMINI_API_KEY="YOUR_API_KEY"
   ```

### Use a Vertex AI API key:

Alternatively, use Vertex AI:

1. Generate a key from [Google Cloud](https://cloud.google.com/vertex-ai/generative-ai/docs/start/api-keys).
2. Set environment variables:

   ```bash
   export GOOGLE_API_KEY="YOUR_API_KEY"
   export GOOGLE_GENAI_USE_VERTEXAI=true
   ```

For detailed authentication options, see the [authentication guide](./docs/cli/authentication.md).

## Examples

Once Phoenix CLI is running, you can start interacting with AI from your shell.

You can start a project from a new directory:

```sh
cd new-project/
phoenix
> Write me a Discord bot that answers questions using a FAQ.md file I will provide
```

Or work with an existing project:

```sh
git clone https://github.com/phoenix-ignite/phoenix-cli
cd phoenix-cli
phoenix
> Give me a summary of all of the changes that went in yesterday
```

### Next steps

- Learn how to [contribute to or build from the source](./CONTRIBUTING.md).
- Explore the available **[CLI Commands](./docs/cli/commands.md)**.
- If you encounter any issues, review the **[troubleshooting guide](./docs/troubleshooting.md)**.
- For more comprehensive documentation, see the [full documentation](./docs/index.md).
- Take a look at some [popular tasks](#popular-tasks) for more inspiration.
- Check out our **[Official Roadmap](./ROADMAP.md)**

### Troubleshooting

Head over to the [troubleshooting guide](docs/troubleshooting.md) if you're
having issues.

## Popular tasks

### Explore a new codebase

Start by `cd`ing into an existing or newly-cloned repository and running `phoenix`.

```text
> Describe the main pieces of this system's architecture.
```

```text
> What security mechanisms are in place?
```

### Work with your existing code

```text
> Implement a first draft for GitHub issue #123.
```

```text
> Help me migrate this codebase to the latest version of Java. Start with a plan.
```

### Automate your workflows

Use MCP servers to integrate your local system tools with your enterprise collaboration suite.

```text
> Make me a slide deck showing the git history from the last 7 days, grouped by feature and team member.
```

```text
> Make a full-screen web app for a wall display to show our most interacted-with GitHub issues.
```

### Interact with your system

```text
> Convert all the images in this directory to png, and rename them to use dates from the exif data.
```

```text
> Organize my PDF invoices by month of expenditure.
```

### Uninstall

Head over to the [Uninstall](docs/Uninstall.md) guide for uninstallation instructions.

## About This Fork

Phoenix CLI is a community-maintained fork of Google's Gemini CLI, created by [phoenix-ignite](https://github.com/phoenix-ignite) to address specific issues and provide enhanced functionality.

**Original Project:** [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)

## Terms of Service and Privacy Notice

For details on the terms of service and privacy notice, see the [Terms of Service and Privacy Notice](./docs/tos-privacy.md).
