# filetypes.lammps.conf

### What?
filetypes.Lammps.conf is a setting file for highlighting [Lammps](https://lammps.sandia.gov/)([Github](https://github.com/lammps/lammps)) syntax in [Geany](https://www.geany.org/)([Github](https://github.com/geany/geany)).

### How?

1. put filetypes.lammps.conf to ~/.config/geany/filedefs
1. in _.config/geany_ add `lammps=*.lmp;in.*;` under `[extensions]` 
```
[Extensions]
...
lammps=*.lmp;in.*;
...
```
and `lammps;`  under `[Groups]`
```
[Groups]
...
Script=...;lammps;
...
```
