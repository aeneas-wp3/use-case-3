
Recipes for building Singularity containers
---


To build (requires sudo):

```bash
sudo singularity build rmsynth.simg Singularity.version1

export SINGULARITY_BINDPATH=/path/on/host/data:/mnt
./rmsynth.simg /mnt/NGC6251.par -s
```


To run from [Singularity Hub](https://www.singularity-hub.org/collections/1459):

```bash
export SINGULARITY_BINDPATH=/path/on/host/data:/mnt
singularity run shub://aeneas-wp3/use-case-3 /mnt/NGC6251.par -s
```
