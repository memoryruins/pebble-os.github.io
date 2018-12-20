---
layout: default
---

Pebble is a microkernel and userspace written in Rust. It is still in very early development.

* Pebble is **not** a UNIX
* Processes communicate through message passing facilitated by the kernel
* Drivers live in userspace
* There are no system calls except to yield to the kernel
