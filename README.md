# Rubiks releases

Public releases of the Rubiks agent harness, the agent behind
[Rubiks Workspace](https://rubiksworkspace.com) and the
[Rubiks IDE](https://github.com/rubiksworkspace/Rubiks-IDE).

## Install

On an Apple silicon Mac:

```bash
curl -fsSL https://github.com/rubiksworkspace/rubiks-releases/releases/latest/download/install.sh | sh
```

Each [release](https://github.com/rubiksworkspace/rubiks-releases/releases) also has a
DMG for a double-click install. Once installed, `prime-agent update` moves to the newest
release, and the Rubiks IDE keeps it up to date on its own.

## Reporting problems

Open an [issue](https://github.com/rubiksworkspace/rubiks-releases/issues). Please leave out
API keys, tokens, private prompts and other sensitive information. Report security
vulnerabilities privately to the maintainers instead.

## License

The files in this repository (this README and the install scripts) are released
under the [MIT License](LICENSE).

The Rubiks binaries attached to the releases are **not** covered by the MIT License.
They are proprietary software, Copyright (c) 2026 The Rubiks Workspace authors, all
rights reserved, and you may use them only under the terms that come with them. They
include third-party components under their own licenses, including Prime Agent by
Prime Intellect (MIT); see the `NOTICE` file shipped inside each release.
