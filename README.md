# bgpsh

Run bgpctl interactively in context of a given rdomain.
This crude scipt spares one from typing `bgpctl -s /var/run/bgpd.sock.<rdomain>` for every single command.

## Usage

```shell
bgpsh <rdomain>
```

Essentially the scripts appends all input to `bgpctl -s /var/run/bgpd.sock.<rdomain>`

Exit with ^D (EOF)
