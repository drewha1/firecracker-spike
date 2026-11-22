# Firecracker venue probe
Date (UTC): 2026-11-22T17:53:37Z
Runner OS: Linux
Kernel: 7.0.0-1020-azure / Arch: x86_64

## KVM
/dev/kvm: PRESENT
vmx/svm flag count: 4

## Firecracker
Latest release: v1.18.0
Firecracker v1.18.0

2026-11-22T17:53:37.584734090 [anonymous-instance:main] Firecracker exiting successfully. exit_code=0

## Boot test
kernel: downloaded
rootfs: downloaded
 <- boot-source
 <- drive
 <- machine-config
 <- start
MICROVM: BOOTED
--- firecracker log tail ---
This system has been minimized by removing packages and content that are
not required on a system that users do not log into.

To restore this content, you can run the 'unminimize' command.
root@ubuntu-fc-uvm:~# firecracker stopped (guest destroyed)
