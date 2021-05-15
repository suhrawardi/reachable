# Reachable

Generates some csv files with popularity, reach and shortest paths of some
network nodes.
There is an example input file [./input/edges.csv](./input/edges.csv) which you
can replace.

## Requirements

You need to install [Souffle](https://souffle-lang.github.io/).
The ./run.sh script works on my Mac but the C++ compilation might fail on other
machines.


## Howto?


Replace the file called [edges.csv](./input/edges.csv) in the input directory
and run:

    $ ./run.sh

Some csv files are placed in the [output](./output) directory.
