# CLI Tool Template

Use for a command-line tool with repeatable inputs and outputs.

## Design
- Define commands, arguments, flags, and exit codes.
- Validate input and provide actionable error messages.
- Support `--help`, version output, and non-interactive mode.
- Keep stdout for results and stderr for diagnostics.
- Make destructive actions require explicit confirmation or a dry-run option.

Add unit tests for parsing and behavior, integration tests for filesystem/network operations, and installation instructions for supported platforms.
