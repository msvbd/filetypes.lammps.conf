# filetypes.lammps.conf

## What
filetypes.Lammps.conf is setting file for highlighting of [Lammps](https://lammps.sandia.gov/)(https://github.com/lammps/lammps) syntax in [Geany](https://www.geany.org/)(https://github.com/geany/geany).

## How to use

1. put filetypes.Lammps.conf to ~/.config/geany/filedefs
1. to _.config/geany_ add `Lammps=*.lmp;in.*;` under `[extensions]`

```
[Extensions]
...
Lammps=*.lmp;
...
```

and `Lammps;`  under `[Groups]`

```
[Groups]
...
Script=...;Lammps;
...
```
