# sourcejedi.ccache #

This role installs `ccache`.

On Debian-based distributions, this role automatically enables `ccache`
for all users by adding `/usr/lib/ccache` to `PATH` when they log in.
On Fedora Linux, this is already implemented by the `ccache` package itself.


## Requirements

This should work to install `ccache` on any distribution that has a package for it.
But it's probably most useful on Debian-based distributions.


## License

This role is licensed GPLv3, please open an issue if this creates any problem.
