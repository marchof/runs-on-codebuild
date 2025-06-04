# runs-on-codebuild

Test project to run GitHub actions on AWS CodeBuild

# GPU Specs

## 4 vCPUs, 16 GiB memory, GPU-enhanced

* Queue time: 0-180s
* Provisioning time: 170s

    *-display:1
        description: 3D controller
        product: GA102GL [A10G]
        vendor: NVIDIA Corporation
        physical id: 1e
        bus info: pci@0000:00:1e.0
        version: a1
        width: 64 bits
        clock: 33MHz
        capabilities: bus_master cap_list
        configuration: driver=nvidia latency=0
        resources: iomemory:80-7f iomemory:100-ff irq:10 memory:fd000000-fdffffff memory:800000000-fffffffff memory:1000000000-1001ffffff

## 32 vCPUs, 256 GiB memory, GPU-enhanced

* Queue time: 4:45h
* Provisioning time: 180s

    *-display:1-4
        description: 3D controller
        product: GA102GL [A10G]
        vendor: NVIDIA Corporation
        physical id: 1b
        bus info: pci@0000:00:1b.0
        version: a1
        width: 64 bits
        clock: 33MHz
        capabilities: bus_master cap_list
        configuration: driver=nvidia latency=0
        resources: iomemory:380-37f iomemory:580-57f irq:11 memory:f9000000-f9ffffff memory:3800000000-3fffffffff 
