
## MAC

* [MAC](https://en.wikipedia.org/wiki/Mandatory_access_control)
* [MLS](https://en.wikipedia.org/wiki/Multilevel_security)

## Models

* [Bell-Lapadula](https://en.wikipedia.org/wiki/Bell%E2%80%93LaPadula_model)
* [Biba](https://en.wikipedia.org/wiki/Biba_Model)
* [Clark-Wilson](https://en.wikipedia.org/wiki/Clark%E2%80%93Wilson_model)

## OS implementations

### Linux

* [LSM](https://www.kernel.org/doc/html/v4.16/admin-guide/LSM/index.html)
* [seccomp]()
* [SELinux]()
* [AppArmor]()

### FreeBSD

* [mac options](http://www.freebsd.no/doc/handbook/mac.html)

# Processes

## Monolithic kernels

* [Containers]()
* [FreeBSD jails](http://www.freebsd.no/doc/handbook/jails.html)

## Microkernels

* the minimal set of tools needed to implement an OS
* use, e.g., virtual address spaces for more than just process isolation (for drivers, file systems, and more)
* has a much smaller [trusted computing base](https://en.wikipedia.org/wiki/Trusted_computing_base)
* [L4 family](http://l4hq.org/) often used as hypervisors
* [about](https://en.wikipedia.org/wiki/Microkernel)
* [genode](https://genode.org/documentation/general-overview/index)
* [Muen](https://muen.codelabs.ch/)
    * separation kernel
    * can run VMs, and MirageOS unikernels directly
    * written in Ada/SPARK (strict subset, contract-based, supports formal verification)
* [minix3](http://www.minix3.org/)
    * see also: Operating Systems Design and Implementation, 3rd Edition
* [sel4](https://sel4.systems/)

## Unikernels
