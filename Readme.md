msgpack decoder for beautiful [cswank/kcli](https://github.com/cswank/kcli) project

### build
```
sh build.sh
```

this command will create ```msgpack.so``` file; this is the compiled decoder itself;

### run kcli with decoder
```
kcli -d ./msgpack.so
```