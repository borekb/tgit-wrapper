# `tgit` wrapper for TortoiseGitProc.exe

All TortoiseGit dialogs can be opened from command-line by running something like:

    "C:\Program Files\TortoiseGit\bin\TortoiseGitProc.exe" /command:log /path:. /rev:sha1

(see [all supported commands](http://tortoisegit.org/docs/tortoisegit/tgit-automation.html)). This wrapper allows simpler execution like:

    tgit log /rev:sha1

Just add it to PATH.