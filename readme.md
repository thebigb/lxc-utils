# LXC Utils

## What is this?

This is a small set of shorthand LXC commands and complementing utilities.

## Overview

```
lxb        Short for 'lxc-start -n', checks whether the container exists
           before attempting to start it.

lxs        Short for 'lxc-stop -n'.

lxa        Short for 'lxc-attach -n', starts container if not started.

lxc        Short for 'lxc-console -n', starts container if not started.

lxi        Short for 'lxc-info -n'

lxclone    Creates a linked clone using overlayfs, and depending on the
           base container does some IDE provisioning.

lxconf     Opens the configuration file for the specified container in
           the default text editor.

lxlog      Opens the container's log file in less

lxdiag     Runs 'lxc-start' with log priority 'TRACE' and opens the log
           in less.

```

## Todo

- [ ] Remove static IP usage from `lxclone`
- [ ] Add more PHPStorm config templates
- [ ] Make config templates smarter (detect existing entries)
- [ ] Make installer packages deb/rpm
- [ ] Make config tooling more generic and multi-purpose (e.g. also get summaries from existing configuration)
