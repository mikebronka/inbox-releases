# Update files

Inbox (from 0.3.28 on) looks here for the newest version of its own system:
`windows-x86_64.json`, `linux-x86_64.json`, `darwin-aarch64.json`, `darwin-x86_64.json`.
Each one describes the newest release built for that system, so a release for some systems
only does not hide the newest version of the others. They are written when a release is
published; the packages themselves are on the [releases page](https://github.com/mikebronka/inbox-releases/releases).
