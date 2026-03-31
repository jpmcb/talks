# stereOS: An open source NixOS based Linux distro for AI

AI agents need real compute infrastructure to do real work.
They need file systems, networks, container infra, and standard Linux tooling.
But giving Claude Code unfettered access to your development environment or laptop is a recipe for disaster and dropped db tables!

The community has adopted a few different ways to manage the non-deterministic
nature of AI agent workloads: containers, Firecracker, dedicated VMs, and much more.
Each comes with tradeoffs, some worse than others.

stereOS takes a different approach that can conform to many different shapes:
a free and open source NixOS based operating system with deeply integrated gVisor
sandboxing and read only rootfs.

In this talk, we'll discuss the various approaches one can take for running,
managing, and sandboxing AI agent workloads and where a bespoke AI focused operating system
fits into that picture. We'll also discuss the technological, Linux build, distribution pipeline,
and community hurdles to provide such a system into the open source ecosystem.

https://github.com/papercomputeco/stereOS
