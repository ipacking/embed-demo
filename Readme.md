# embed

## debug gdb
```
cargo embed
gdb xxx
target remote :1337
```

## debug lldb
```
cargo embed
lldb xxx
platform select remote-gdb-server
process connect connect://127.0.0.1:1337
```