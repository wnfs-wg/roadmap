# The WNFS Roadmap

View the public WNFS roadmap here: https://github.com/orgs/wnfs-wg/projects/1/views/1

The roadmap is where we provide information on what we aim to improve in WNFS, what the priorities for that are and when we'll probably get to that. It can serve as a sort-of vision for where WNFS is going and allows *you* to figure out where you can help accelerate our shared roadmap!

If you want to reach out to us about this roadmap, [creating a discussion](https://github.com/wnfs-wg/roadmap/discussions/new) is a great place to start.


## What is WNFS?

We've started to build the WebNative File System because:
- User data should be content-addressable so users can take it wherever they want it to go to keep it safe, available and persisted.
- We want user data to be encrypted at rest with keys owned by users.
- We need space for users to attach metadata.
- User data should support multi-tenancy, so it should e.g. reconcile changes from multiple devices.
- Users should be able to use the [POLA](https://en.wikipedia.org/wiki/Principle_of_least_privilege) when sharing read or write access.
- We want to hide file size & DAG structure ('metadata') for encrypted data.
  (Encrypting content but exposing the links is not an option. Persistent identities (e.g. public keys) per file/directory is not an option.)

It is an open standard and everyone should be empowered to help build this!
We don't think WNFS can solve every use case, but we surely hope by developing this in the open we avoid encrypting data in various different formats.

Find out more about WNFS at:
- [The organization page](https://github.com/wnfs-wg/)
- [The specification](https://github.com/wnfs-wg/spec)
- [The repository for a rust implementation `rs-wnfs`](https://github.com/wnfs-wg/rs-wnfs)

## How do I contribute?

Reach out to us! [Create a discussion](https://github.com/wnfs-wg/roadmap/discussions/new) in this repository.
