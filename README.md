# asyncutils

Some useful utilities for async in Nim. Supports C / C++ / NodeJS / JS backend.


Example usage of `fastsync` pragma:

```
proc ex(e: SyncExample | AsyncExample) {.multisync.}

proc ex(e: Example) {.fastsync.}
```

Thanks to @beef331