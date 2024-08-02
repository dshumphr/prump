# Prump: A Prompt-Dumping Platform

Prump is simply a place for dumping your prompts. It serves as a repository for JSON files containing prompting results. The intention is to share prompting data freely.

## Format

```json
[
    {
        "timestamp": "ISOSTRING",
        "model": "model descriptor",
        "systemPrompt": "system prompt",
        "userPrompt": "user prompt",
        "response": "full response message",
        "applicationType": "How the prompt was used (eg. discarded, applied, etc)"
    }
]
```

Currently, the filename is based on GitHub user id, although this might be re-sharded in the future.
The specifics of applicationType come from [Tad](https://github.com/dshumphr/tad), an AI coding VS Code extension.

## Usage
Use my prompt dump however you like.

## Contributing
If you'd like to contribute data to prump, feel free to fork and send over PRs.