A tmux colorscheme based on Ciapre

### Installation with [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm) (recommended)

Add plugin to the list of TPM plugins in `.tmux.conf`:

    set -g @plugin 'konart/ciapre.tmux'

Hit `prefix + I` to fetch the plugin and source it.

Reload your tmux configuration and the colorscheme should be loaded.

### Manual Installation

Clone the repo:

    $ git clone https://github.com/konart/ciapre.tmux ~/clone/path

Add this line to the bottom of `.tmux.conf`:

    run-shell ~/clone/path/ciapre.tmux

Reload TMUX environment:

    # type this in terminal
    $ tmux source-file ~/.tmux.conf
