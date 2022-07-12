# Build system

Create executable:

```zig
zig build-exe ./tiny-hello.zig -O ReleaseSmall --strip -fsingle-threaded
```

create doc:

```
zig build-lib -femit-docs tiny-hello.zig -target native-windows
```
