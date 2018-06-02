# sourcejedi.ccache #

Install `ccache`, the compiler cache.

This role is most useful on Debian-based distributions,
as it will automatically enable `ccache` for all users,
by adding `/usr/lib/ccache` to `PATH` at login time.
On Fedora Linux, this is already implemented by the `ccache` package itself.


## Requirements

This should work to install `ccache` on any distribution that has a package for it.

## License

This role is licensed GPLv3, please open an issue if this creates any problem.
