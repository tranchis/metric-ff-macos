# MetricFF

Metric-FF is a domain independent planning system developed by Joerg Hoffmann. The system is an extension of the FF planner to (ADL combined with) numerical state variables, more precisely to PDDL 2.1 level 2, yet more precisely to the subset of PDDL 2.1 level 2 described below with the algorithmic principles. The system is implemented in C.

## Compilation

```bash
$ make ff
```

## Running

```bash
./ff -o domain.pddl -f problem.pddl
```

## License

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA  02111-1307, USA.
