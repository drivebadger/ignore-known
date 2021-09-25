This is an extension for Drive Badger. It provides a sample `ignore.uuid` file, containing a list of partition UUIDs, that should be ignored by Mobile Badger after plugging in.

### Installing

This particular configuration repository contains only well-known partition UUIDs - so you can clone and use it directly.

To install, just clone it as `/opt/drivebadger/config/ignore-known` local directory on your Drive Badger drive.

This way, you are able to update it in the future by a single command `/opt/drivebadger/update.sh` (it automatically runs
`/opt/drivebadger/internal/generic/rebuild-uuid-lists.sh` after update - if you want to update this repository alone,
remember to run this script manually).

Multiple `ignore.uuid` files are allowed - each in separate repository.


### More information

- [Drive Badger main repository](https://github.com/drivebadger/drivebadger)
- [Drive Badger wiki](https://github.com/drivebadger/drivebadger/wiki)
- [description, how configuration repositories work](https://github.com/drivebadger/drivebadger/wiki/Configuration-repositories)
