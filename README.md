# Instructions to access the open source code used in Google Nest products

[TOC]

Open source code for various Google Nest Wifi Pro, Nest spreaker and displayer
versions after released after Oct, 2022 can be found below. For previous
versions please refer to the [Google Support page](https://support.google.com/product-documentation/topic/6355909).

## Nest Wifi products

### Nest Wifi Pro

The open source manifests for Nest Wifi Pro releases can be found under
[nest-wifi-pro](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest-wifi-pro)
folder. For example, to download the code specified in `308974.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest-wifi-pro/308974.xml
$ repo sync
```

## Google Nest speakers and smart displays

### Google Nest Hub 7", 2nd gen

The open source manifests for Nest Wifi Pro releases can be found under
[sabrina](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/sabrina)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m sabrina/324896.xml
$ repo sync
```

### Nest Audio

The open source manifests for Nest Wifi Pro releases can be found under
[prince](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/prince)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m prince/324896.xml
$ repo sync
```

### Google Nest Mini v2

The open source manifests for Nest Wifi Pro releases can be found under
[valens](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/valens)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m valens/324896.xml
$ repo sync
```

### Google Nest Mini

The open source manifests for Nest Wifi Pro releases can be found under
[joplin](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/joplin)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m joplin/324896.xml
$ repo sync
```

### Google Home

The open source manifests for Nest Wifi Pro releases can be found under
[chrip](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/chirp)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m chirp/324896.xml
$ repo sync
```

## Obtain the `repo` tool

Repo is a tool built on top of Git. Repo helps manage many Git repositories. You
can download and learn more about it at
https://gerrit.googlesource.com/git-repo/+/refs/heads/master/README.md
