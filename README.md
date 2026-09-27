[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Termux (`termux`)

The `termux` command source repository,
which launches the
[Termux android terminal application](
  https://github.com/termux/termux-app).

The `termux` command is currently not included
by default in the Termux android terminal
application.

To run the `termux` command you need to
install the `termux` package.

The `termux` package is not available in
Termux android terminal application default
application lists so you can't install
it neither with `pkg install termux` nor
with `apt install termux` nor with
`pacman -S termux`.

The easiest way to install and upgrade
the `termux` package is doing it from the
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store.

After installing the Ur on Termux,
you can run

```bash
ur \
  termux
```

to install and run the `termux` command,
which will bring up the Termux android
application, like you can see into the
following video.

A
[Gur](
  https://github.com/themartiancompany/gur)
mirror of the Ur package is published on
[`termux-bin-ur`](
  https://github.com/themartiancompany/termux-bin).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## Installation

The programs in this source repo
can be installed from source directly using GNU Make.

```bash
make \
  install
```

The `termux` command depends on the
[Android Activity Utilities](
  https://github.com/themartiancompany/android-activity-utils).

## Documentation

The `termux` command launches and brings in focus
the Termux application.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
