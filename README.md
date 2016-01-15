# Awesome Fish Shell

[![Awesome][awesome-badge]][awesome-link]

A [curated](https://github.com/sindresorhus/awesome/blob/master/awesome.md#only-awesome-is-awesome) list of awesome tools, utilities, guides and other cool nuggets inspired by [_Awesome_](https://github.com/sindresorhus/awesome) for the amazing [Fish Shell][fish-shell].


:pencil2: [**Add item to list...**](https://github.com/bucaran/awesome-fish/fork)
> ## Table of Contents
> + [Plugin Managers](#plugin-managers)
> + [Test Frameworks](#test-frameworks)
> + [Utilities](#utilities)
> + [Prompts](#prompts)
>   + [Powerline](#powerline-prompts)
>   + [Other](#other-prompts)


### Plugin Managers

#### [Fisherman](https://github.com/fisherman/fisherman) :star::star::star::star:
> A fast, modern plugin system and CLI toolkit for Fish.

Fisherman uses a flat tree structure that adds no cruft to your shell, making it as fast as no Fisherman. The cache mechanism lets you query the index offline and enable or disable plugins as you wish.

#### [fundle](https://github.com/tuvistavie/fundle) :star::star:
> A minimalist package manager for fish.

All plugins are installed/updated using git, so the only requirement is to have git installed and on the path (and well, fish, obviously).

#### [Tacklebox](https://github.com/justinmayer/tacklebox/) :star:
> Framework for organizing and sharing fish shell functions.

Tacklebox is a framework for Fish that makes it easy to organize and share collections of useful shell functions, tools, and themes.


### Test Frameworks

#### [Fishtape](https://github.com/fisherman/fishtape) :star::star::star::star:
> TAP producer and test harness for fish.

Fishtape is a TAP (Test Anything Protocol) producer and test harness for fish. This utility reads one or more files, or the standard input if no files are given, and executes test blocks producing a TAP stream.


### Utilities

#### [bass](https://github.com/edc/bass) :star::star:
> Make Bash utilities usable in Fish.

Bass is created to make it possible to use bash utilities in fish without any modification. It works by capturing what environment variables are modified by the utility of interest, and replay the changes in fish.

#### [Shark](https://github.com/bucaran/shark) :star::star::star::star:
> Sparkline Generator.

Shark reads the standard input extracting numeric values and produces a stream of UTF-8 block characters of increasing  height.


### Prompts

> :warning: Powerline prompts look better with [Powerline Patched Fonts](https://github.com/powerline/fonts).

+ [Shellder](https://github.com/simnalamburt/shellder) :star::star::star::star:
Powerline prompt optimized for speed, inspired by [seoul256.vim](https://github.com/junegunn/seoul256.vim).

+ [Scorphish](https://github.com/oh-my-fish/theme-scorphish) :star::star::star:

Vigorous multi-line, [epaulette](https://en.wikipedia.org/wiki/Epaulette)-evoking, angle bracket prompt.

+ [Agnoster](https://github.com/oh-my-fish/theme-agnoster) :star::star:
Powerline prompt optimized for Solarized Dark and Git users.

+ [Bobthefish](https://github.com/oh-my-fish/theme-bobthefish) :star::star:
A Powerline-style, Git-aware fish theme optimized for awesome.

+ [Chris Morrell's](https://github.com/oh-my-fish/theme-cmorrell.com) :star::star:
Original, minimal base prompt featuring left / right artifacts.


## Contributing

Fork, add and send your PR. If you wish to remove an item from the list please [open][issues] an issue first.

<hr>

:tropical_fish: [CC0 1.0 Universal](LICENSE)


<!-- Other Links -->

[issues]: https://github.com/bucaran/awesome-fish/issues
[fish-shell]: https://github.com/fish-shell/fish-shell
[awesome-link]:https://github.com/sindresorhus/awesome
[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
