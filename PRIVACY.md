# Privacy Policy — AI CLI Launcher

_Last updated: 2026-06-03_

AI CLI Launcher ("the plugin") is a macOS-only JetBrains IDE plugin that launches
local AI CLI tools in an external terminal at your project root. This policy
explains what data the plugin handles.

## Summary

The plugin is local-first. It does not collect, transmit, or sell any personal
data. It contains no telemetry, no analytics, and makes no network requests of
its own.

## Data the plugin stores locally

The plugin saves its settings on your machine through the standard JetBrains
settings storage:

- the selected terminal application path;
- the list of configured AI commands (display name and command);
- the current-file context mode and the paste delay value.

This data never leaves your computer.

## Data the plugin does NOT collect

- It does not read, upload, or transmit your source code.
- It does not capture the prompts you type into the AI CLI.
- It does not collect API keys, credentials, or tokens.
- It does not track usage or identify you.

## Clipboard and macOS automation

When the "current file" context mode is enabled, the plugin uses the system
clipboard and macOS System Events automation to prefill the relative file path
into the terminal. This is best-effort, processed entirely on your machine, is
never auto-submitted, and the plugin restores your previous clipboard contents
when possible. It relies on the macOS Accessibility/Automation permission you
grant to your IDE.

## Debug report

The "Copy Debug Report" action generates diagnostic text (plugin version, IDE,
OS, terminal information, and AI command checks) and copies it to your clipboard.
Nothing is sent anywhere. If you choose to include it in a bug report, you decide
what to post — review and remove anything sensitive first.

## Third-party services

- The local AI CLI tools you launch (for example Codex or Claude) are independent
  programs governed by their own privacy policies; the plugin only opens them.
- If you submit an issue to the public support repository on GitHub, the
  information you provide is handled under GitHub's privacy policy.

## Contact

Questions or requests: https://github.com/GuJin/ai-cli-launcher-support/issues

## Changes

Any updates to this policy will be published in the support repository.
