# ABHPC slurm adapter for openSCOW

系统需求：
[Buf](https://buf.build/docs/installation/)

[Git>=2.18.0](https://github.com/git/git)

```bash
module load git/2.18.0

# Generate code from latest scow-slurm-adapter
make protos

# Build
make build
```