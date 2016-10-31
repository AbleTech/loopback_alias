# loopback_alias
Creates private 127.0.0.x IP address aliases on OSX

## Running

```
git clone git@github.com:AbleTech/loopback_alias.git
cd loopback_alias
./loopback_alias
```

You can then run `ipconfig` and you should see the 20 private records of `127.0.0.1`-`127.0.0.20`.

## Installation

Use the following additional command to apply the alias records on boot.

```
./install
```

## Uninstall

```
sudo rm /Library/LaunchDaemons/nz.abletech.loopback_alias.plist
```
