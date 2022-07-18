# TopoMojo Install

This is an addition to the original k3s-production Crucible installation to add TopoMojo.
## Requirements

Before running the script to install TopoMojo, please have these requirements:

- DVS
- Two VMFS
- One NFS

DVS can have just one uplink. **Please do not forget to add the correct permissions to the topomojo-svc account.**

After following the previous steps of installing Crucible and having the correct requirements, you should be able to fully install TopoMojo by filling out the remainder of the env specific to TopoMojo and running the `setup-topomojo` script.

## What the script is doing

First, it adds a PersistentVolume and a PersistentVolumeClaim for TopoMojo to bind to. Then, helm will install TopoMojo using the env file.
