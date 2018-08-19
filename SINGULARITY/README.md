
Recipes for building Singularity containers
---

To build (requires sudo):

$ sudo singularity build rmsynth.simg Simgularity

$ export SINGULARITY_BINDPATH=/path/on/host/data:/mnt
$ ./rmsynth.simg /mnt/NGC6251.par -s


To run from Singularity Hub:

$ export SINGULARITY_BINDPATH=/path/on/host/data:/mnt
$ singularity run shub://aeneas-wp3/use-case-3 /mnt/NGC6251.par -s
