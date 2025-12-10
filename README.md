# Platform Test E2E

This repository is used for end-to-end testing of the devs.do SDLC automation platform.

## Overview

The devs.do platform automates the software development lifecycle using Claude Code. When issues are assigned or labeled, the platform:

1. **Development Phase**: Claude Code analyzes the issue and implements the requested changes
2. **Code Review Phase**: A separate Claude Code instance reviews the PR for quality
3. **Merge Phase**: After approval, the PR is automatically merged

## Usage

Issues in this repository will be automatically worked on by the devs.do platform.

### Triggering Development

- Assign an issue to `tomdolen` (the developer bot)
- Or add the `devs.do` label to an issue
- Or mention `@devs.do` in a comment

### Monitoring Progress

Visit `https://devs.do/nathanclevenger/platform-test-e2e/{issue_number}` to see the session status.

## Testing

```bash
npm install
npm test
```
