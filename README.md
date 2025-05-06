# Proto Plugins
A few additional plugins for [proto](https://github.com/moonrepo/proto).

## Available Plugins:
- [air-verse/air](https://github.com/air-verse/air)
- [dominikh/go-tools/staticcheck](https://github.com/dominikh/go-tools)
- [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc)
- [golang-migrate/migrate](https://github.com/golang-migrate/migrate)
- [mgechev/revive](https://github.com/mgechev/revive)

## Install
```sh
# air-verse/air
proto plugin add air "source:https://raw.githubusercontent.com/jamesukiyo/proto-plugins/master/air.toml"
proto install --pin air

# dominikh/go-tools/staticcheck
proto plugin add staticcheck "source:https://raw.githubusercontent.com/jamesukiyo/proto-plugins/master/staticcheck.toml"
proto install --pin staticcheck

# sqlc-dev/sqlc
proto plugin add sqlc "source:https://raw.githubusercontent.com/jamesukiyo/proto-plugins/master/sqlc.toml"
proto install --pin sqlc

# golang-migrate/migrate
proto plugin add migrate "source:https://raw.githubusercontent.com/jamesukiyo/proto-plugins/master/migrate.toml"
proto install --pin migrate

# mgechev/revive
proto plugin add revive "source:https://raw.githubusercontent.com/jamesukiyo/proto-plugins/master/revive.toml"
proto install --pin revive
```
