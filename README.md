# Instructions to access the open source code used in Google Nest products

## Nest Wifi Pro

The open source manifests for Nest Wifi Pro releases can be found under
[nest-wifi-pro](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest-wifi-pro)
folder. For example, to download the code specified in `308974.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest-wifi-pro/308974.xml
$ repo sync
```

## Nest Wifi, Google Wifi and OnHub products

See https://chromium.googlesource.com/
