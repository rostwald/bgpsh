# bgpsh

Run bgpctl interactively in context of a given rdomain.
This crude scipt spares one from typing `route -T<rdomain> exec bgpctl` for every single command.

## Usage

```shell
bgpsh <rdomain>
```

Essentially the scripts appends all input to `route -T<rdomain> exec bgpctl`

Exit with ^D (EOF)
