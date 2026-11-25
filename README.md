# netfs

A plan9 inspired network filesystem for Linux.

`netfs` exposes network resources and operations through a filesystem interface, following Plan9's `/net` architecture.

Instead of interacting with networking exclusively through conventional socket APIs and specialized utilities, applications can manipulate connections using familiar filesystem operations: opening, reading, writing, and closing files.

The project aims to bring Plan9 resource oriented approach to networking to Linux, using userspace components and the existing Linux networking stack.

### Goals

- Expose TCP and UDP connections as filesystem resources.
- Provide control, data and status interfaces for connections.
- Support concurrent connections and independent processes.
- Explore filesystem-based resource management.
- Eventually support namespace isolation and remote access through 9P.
