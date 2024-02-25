
## Getting started
Console client for [Olivia](https://github.com/MehraB832/olivia_core)

<p align="center">
<br>
<img src="./olivia-cc.svg">
<br>
</p>

### How to use it.
For the first time - you can simple run - ./main
Download it from [here](https://github.com/MehraB832/olivia_console/releases)
It's will create new default config file, and new logfile.

#### Example of config file:
```json
{
 "port": "8080",
 "host": "localhost",
 "debug_level": "error",
 "bot_name": "Olivia",
 "user_token": "52fdfc072182654f163f5f0f9a621d729566c74d10037c4d7bbb0407d1e2c64981855ad8681d0d86d1e91e00167939cb6694"
}
```

#### Description:
* `bot_name` - name for your bot (default - Olivia)
* `debug_level` - verbosity (default - error)
* `host` - host where is running server part of olivia (default - localhost)
* `port` - the same about port
* `user_token` - your own token (default - generated on the first run)

## Licence
<p align="center">
  <img src="https://i.imgur.com/9Xxtchv.png" height="90">
</p>

Licensed under MIT

module github.com/MehraB832/olivia_console

go 1.13

require (
	github.com/gookit/color v1.2.5
	github.com/gorilla/websocket v1.4.2
	github.com/olivia-ai/olivia-kit-go v0.0.0-20200516175857-ca943c581b09 // indirect
	github.com/sirupsen/logrus v1.6.0
	golang.org/x/sys v0.0.0-20200513112337-417ce2331b5c // indirect
)
