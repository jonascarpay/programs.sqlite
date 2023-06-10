# programs.sqlite

`programs.sqlite` is the database of binaries provided by [`nixpkgs`](https://github.com/NixOS/nixpkgs).
This script grabs `programs.sqlite` from <https://channels.nixos.org> and version controls it, automatically updating once a week.

I use in my NixOS config for setting the `programs.command-not-found.dbPath` option.
