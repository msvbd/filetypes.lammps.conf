# filetypes.lammps.conf

## What
filetypes.Lammps.conf is setting file for highlighting of [Lammps](https://lammps.sandia.gov/)([Github](https://github.com/lammps/lammps)) syntax in [Geany](https://www.geany.org/)([Github](https://github.com/geany/geany)).

## How to use

1. put filetypes.lammps.conf to ~/.config/geany/filedefs
1. add `Lammps=*.lmp;in.*;` under `[extensions]` in _.config/geany_ 

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
