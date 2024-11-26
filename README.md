Build and run were tested with [Apptainer](https://apptainer.org/) 1.3.4. But as we do not use any fancy features, I expect wide compatibility with Apptainer releases.

## build

Image takes the baseimage from Docker, so no `sudo` is needed.

```
apptainer build image.sif ./visit.def
```

## run

```
apptainer exec image.sif visit
```
