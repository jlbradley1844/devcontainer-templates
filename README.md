# devcontainer-templates

Python, C++, and Jekyll dev container configs that share one common block:
Claude Code + gh + node features, `~/devhome/{claude,memory,shared}` bind mounts,
`CLAUDE_CONFIG_DIR=/home/vscode/.claude`, `GH_TOKEN` passed through from the host,
`remoteUser: vscode`.

    ./new-project python ~/github/my-project

Launch VS Code from a WSL shell (`code .`) with `GH_TOKEN` exported so
`${localEnv:GH_TOKEN}` resolves.
