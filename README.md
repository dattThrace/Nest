# Instructions to access the open source code used in Google Nest products

[TOC]

Open source code for various Google Nest Wifis, Nest spreakers and displays
versions after released after Oct, 2022 can be found below. For previous
versions please refer to the
[Google Support page](https://support.google.com/product-documentation/topic/6355909).

## Nest Wifi products

### Nest Wifi Pro

The open source manifests for Nest Wifi Pro releases can be found under
[nest_wifi_pro](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_wifi_pro)
folder. For example, to download the code specified in `424613.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_wifi_pro/424613.xml
$ repo sync
```

## Google awareness products

### Nest wired indoor

The open source manifests for Nest wired indoor releases can be found under
[nest_wired_indoor](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_wired_indoor)
folder. For example, to download the code specified in `416403.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_wired_indoor/416403.xml
$ repo sync
```

### Nest outdoor

The open source manifests for Nest outdoor releases can be found under
[nest_outdoor](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_outdoor)
folder. For example, to download the code specified in `416403.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_outdoor/416403.xml
$ repo sync
```

### Nest battery doorbell

The open source manifests for Nest battery doorbell releases can be found under
[nest_battery_doorbell](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_battery_doorbell)
folder. For example, to download the code specified in `416403.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_battery_doorbell/416403.xml
$ repo sync
```

### Nest wired doorbell

The open source manifests for Nest battery doorbell releases can be found under
[nest_wired_doorbell](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_wired_doorbell)
folder. For example, to download the code specified in `416403.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_wired_doorbell/416403.xml
$ repo sync
```

## Google Nest streaming products

### Chromecast with Google TV 4K

The open source manifests for the kernel and bootlooder of Chromecast with
Google TV 4K releases can be found under
[chromecast_with_google_tv_4k](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/chromecast_with_google_tv_4k)
folder. For example, to download the code specified in `396134.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m chromecast_with_google_tv_4k/396134.xml
$ repo sync
```

For the device userspace opensource, please
[download AOSP code](https://source.android.com/docs/setup/download/downloading).

### Chromecast with Google TV HD

The open source manifests for the kernel and bootlooder of Chromecast with
Google TV HD releases can be found under
[chromecast_with_google_tv_hd](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/chromecast_with_google_tv_hd)
folder. For example, to download the code specified in `398799.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m chromecast_with_google_tv_hd/398799.xml
$ repo sync
```

For the device userspace opensource, please
[download AOSP code](https://source.android.com/docs/setup/download/downloading).

### Google TV Streamer

The open source manifests for the device-specific kernel code for Google TV
Streamer can be found under
[google_tv_streamer](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_tv_streamer)
folder. For example, to download the code specified in `431402.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_tv_streamer/431402.xml
$ repo sync
```

The remainder of the kernel code for Google TV Streamer is available as the
[GKI kernel source](https://android.googlesource.com/kernel/manifest/+/refs/heads/common-android14-5.15/default.xml).
For the device userspace opensource, please download the
[AOSP code](https://source.android.com/docs/setup/download/downloading).

## Google Nest speakers and smart displays

### Pixel tablet speaker dock

The open source manifests for Pixel tablet speaker dock releases can be found
under
[pixel_tablet_speaker_dock](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/pixel_tablet_speaker_dock)
folder. For example, to download the code specified in `374000.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m pixel_tablet_speaker_dock/374000.xml
$ repo sync
```

### Google Nest Hub 7", 2nd gen

The open source manifests for Nest Wifi Pro releases can be found under
[google_nest_hub_7_2nd_gen](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_nest_hub_7_2nd_gen)
folder. For example, to download the code specified in `324896.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_nest_hub_7_2nd_gen/324896.xml
$ repo sync
```

### Nest Audio

The open source manifests for Nest Audio releases can be found under
[nest_audio](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/nest_audio)
folder. For example, to download the code specified in `415414.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m nest_audio/415414.xml
$ repo sync
```

### Google Nest Mini v2

The open source manifests for Google Nest Mini v2 releases can be found under
[google_nest_mini_v2](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_nest_mini_v2)
folder. For example, to download the code specified in `415414.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_nest_mini_v2/415414.xml
$ repo sync
```

### Google Nest Mini

The open source manifests for Google Nest Mini releases can be found under
[google_nest_mini](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_nest_mini)
folder. For example, to download the code specified in `415414.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_nest_mini/415414.xml
$ repo sync
```

### Google Home

The open source manifests for Google Home releases can be found under
[google_home](https://nest-open-source.googlesource.com/manifests/+/refs/heads/main/google_home)
folder. For example, to download the code specified in `415414.xml`, please run
the following commands.

```shell
$ repo init -u https://nest-open-source.googlesource.com/manifests -b main -m google_home/415414.xml
$ repo sync
```

## Obtain repo

Repo is a tool built on top of Git. Repo helps manage many Git repositories. You
can download and learn more about it at
https://gerrit.googlesource.com/git-repo/+/refs/heads/master/README.md
