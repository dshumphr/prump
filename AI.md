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

Filename is currently based on github user. May shard in some other way in the future.

The specifics of applicationType come from [Tad](https://github.com/dshumphr/tad), an AI coding VS Code extension.

## Usage
Use my prompt dump however you like.