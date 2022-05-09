# pyiron dynamic 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jan-janssen/pyiron-materialdigital-demo/HEAD)

The job class `MydynamicJob` is defined based on the files in the directory `pyiron/resources/dynamic/MydynamicJob`. The directory contains: 

- `input.json` - default input dictionary store in JSON format
- `script.py` - python module which contains the `write_input()` and `collect_output()` functions
- `bin/run_mydynamicjob_0.0.1.sh` - shell script for serial execution
- `bin/run_mydynamicjob_0.0.1_mpi.sh` - shell script for MPI parallel execution

The job class `MyscriptJob` is defined based on the files in the directory `pyiron/resources/template/MyscriptJob`. The directory contains: 

- `input.json` - default input dictionary store in JSON format
- `script.py` - python script to execute the calculation
