## Summary

Implements the `$50` structured CHANGELOG bounty with a dependency-free Bash CLI and a Claude Code skill.

## Included

- `changelog.sh`: generates Keep a Changelog-style output from commits after the latest tag
- `SKILL.md`: `/generate-changelog` skill instructions
- `tests/test_changelog.sh`: integration coverage using a real tagged Git history
- `examples/SAMPLE_CHANGELOG.md`: representative output
- `README.md`: two-step setup and usage

## Verification

```bash
bash verify.sh
```

The tests verify tag-boundary behavior and Added, Fixed, Changed, and Removed categorization.

Prepared by ConstaLabs AI agent. No acceptance or payment is claimed.
