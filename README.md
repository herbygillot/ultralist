# Ultralist
### Simple task management for tech folks.

[![](https://goreportcard.com/badge/github.com/ultralist/ultralist)](https://goreportcard.com/report/github.com/ultralist/ultralist)
[![Build Status](https://travis-ci.org/ultralist/ultralist.svg?branch=master)](https://travis-ci.org/ultralist/ultralist)

Ultralist is a task management system for technical people. It is command-line component that is very fast and stays out of the way. 

Ultralist is based off of the [Getting Things Done](gtd) system. It has a concept of due dates, projects, and contexts.

[![asciicast](https://asciinema.org/a/226005.svg)](https://asciinema.org/a/226005)

Combined with [Ultralist Pro](https://ultralist.io), Ultralist provides a superior task management experience to Todoist, Any.do etc.  The command-line will app _always_ be first and foremost.

**See the [ultralist docs][tdl] for complete documentation.**

[gtd]: http://lifehacker.com/productivity-101-a-primer-to-the-getting-things-done-1551880955
[tdl]: https://ultralist.io/docs

## Is it good?

Yes.  Yes it is.

## Installation

* **Mac OS**: Run `brew install ultralist`.
* **Arch Linux**: May be installed from AUR [ultralist](https://aur.archlinux.org/packages/ultralist/)
* **FreeBSD**: Run `pkg install ultralist` or `cd /usr/ports/deskutils/ultralist && make install clean`
* **Other systems**: Get the correct ultralist binary from the [releases page](https://github.com/ultralist/ultralist/releases).
* If you have Golang installed: Run `go get github.com/ultralist/ultralist`.

Then, follow the [quick start](https://ultralist.io/docs/cli/quickstart/) in the docs to quickly get up and running.

## How does Ultralist relate to Ultralist Pro?

* `ultralist` is this tool.
* [Ultralist Pro](https://ultralist.io) is an enhancement service to the `ultralist` tool.  It allows for synchronization between computers, management of your task lists on the web + mobile, integrations with tools you already use, teams, and more.

## How is this different from todo.txt, Taskwarrior, etc?

[todo.txt](http://todotxt.org/) is great.  But it didn't work well for my needs.

Here's how ultralist compares specifically to todo.txt:
1. **Due dates.** they are a core concept of ultralist but not todo.txt.
1. **Synchronizing.** Syncing is built into the CLI using the [ultralist.io](https://ultralist.io) service.
1. **Active development.** the ultralist CLI is under active development, whereas todo.txt's CLI is not.

## Author

Please send complaints, complements, rants, etc to [Grant Ammons][ga]

## License

Ultralist is open source, and uses the [MIT license](https://github.com/ultralist/ultralist/blob/master/LICENSE.md).

[ga]: https://twitter.com/gammons
