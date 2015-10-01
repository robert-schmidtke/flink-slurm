# flink-slurm
Script that runs an example Flink job on Slurm. Requires the start/stop scripts in this fork: https://github.com/robert-schmidtke/flink/tree/flink-slurm

Run like so:
```bash
sbatch -p<PARTITION> -A<ACCOUNT> flink-slurm-example.sh
```
