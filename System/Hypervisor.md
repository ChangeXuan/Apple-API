# Hypervisor
### Build virtualization solutions on top of a lightweight hypervisor, without the need for thirdparty kernel extensions.
## 概述
The Hypervisor framework provides C APIs for interacting with virtualization technologies in user-space, without the need for writing kernel extensions (KEXTs). As a result, apps created using this framework are suitable for distribution on the Mac App Store.

Hardware-facilitated virtual machines (VMs) and virtual processors (vCPUs) can be created and controlled by an entitled sandboxed user space process, the hypervisor client. The Hypervisor framework abstracts virtual machines as tasks and virtual processors as threads.
