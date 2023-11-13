# Instructions to access the open source code used in Google Nest products

[TOC]

Open source code for various Google Nest Wifis, Nest spreakers and displays
versions after released after Oct, 2022 can be found below. For previous
versions please refer to the [Google Support page](https://support.google.com/product-documentation/topic/6355909).

## Nest Wifi products

### Nest Wifi Pro

The open source manifests for Nest Wifi Pro releases can be found under
[nest_wifi_pro](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_wifi_pro)
folder. For example, to download the code specified in `308974.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_wifi_pro/308974.xml
$ repo sync
```

## Google Nest speakers and smart displays

### Google Nest Hub 7", 2nd gen

The open source manifests for Nest Wifi Pro releases can be found under
[google_nest_hub_7_2nd_gen](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_nest_hub_7_2nd_gen)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_nest_hub_7_2nd_gen/324896.xml
$ repo sync
```

### Nest Audio

The open source manifests for Nest Audio releases can be found under
[nest_audio](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_audio)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_audio/324896.xml
$ repo sync
```

### Google Nest Mini v2

The open source manifests for Google Nest Mini v2 releases can be found under
[google_nest_mini_v2](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_nest_mini_v2)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_nest_mini_v2/324896.xml
$ repo sync
```

### Google Nest Mini

The open source manifests for Nest Nest Mini releases can be found under
[google_nest_mini](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_nest_mini)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_nest_mini/324896.xml
$ repo sync
```

### Google Home

The open source manifests for Google Home releases can be found under
[google_home](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_home)
folder. For example, to download the code specified in `324896.xml`,
please run the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_home/324896.xml
$ repo sync
```

## Obtain repo

Repo is a tool built on top of Git. Repo helps manage many Git repositories. You
can download and learn more about it at
https://gerrit.googlesource.com/git-repo/+/refs/heads/master/README.md
