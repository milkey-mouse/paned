# paned

As a terminal multiplexer, `paned` serves the same basic need as [tmux](https://github.com/tmux/tmux) or [screen](https://www.gnu.org/software/screen/): it enables switching between, disconnecting from, and reconnecting to terminal sessions from one physical (well, virtual) terminal.

Where `paned` differs from its progenitors is in its minimalism: there is no window management functionality beyond switching and detaching; complex layouts of multiple terminal windows is left to a real window manager.

`paned` is a daemon which manages window panes, but in [classic Linus Torvalds fashion](https://github.com/git/git/blob/e83c5163316f89bfbde7d9ab23ca2e25604af290/README#L4-L13) its name also describes how you will feel when it doesn't work right.
