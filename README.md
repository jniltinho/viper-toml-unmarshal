# viper TOML unmarshal example

```console
$ go run main.go
host=localhost port=5432 user=postgres pass=
output=out.txt
main.Config{Db:main.DatabaseConfig{Host:"localhost", Port:"5432", User:"postgres", Pass:""}, Out:main.OutputConfig{File:"out.txt"}}
```


## Links

- https://www.onbirkod.com/reading-from-and-writing-to-toml-config-file-in-go-golang/
- https://github.com/spf13/viper
