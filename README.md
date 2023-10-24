# floor-demo
FLOOR is a proof-of-concept SQLite VFS that reimplements
write-ahead logging (WAL). It uses proposed web platform features JavaScript
Promise Integration (JSPI, aka stack switching) and FileSystemSyncAccessHandle
multiple readers and writers.

Currently running the [demo](https://rhashimoto.github.io/floor-demo/demo/)
requires Chrome 120+ with experimental flags
#enable-experimental-webassembly-stack-switching and
#file-system-access-locking-scheme manually enabled.
