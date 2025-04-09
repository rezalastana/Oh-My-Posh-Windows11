# Langkah Install Oh-My-Posh pada Windows 10/11 🌸

## Install powershell

Anda dapat melakukan installasi powershell pada windows store, lalukan penyesuain setting pada command promt anda dengan default _powershell_

## Install Oh-My-Posh

Anda dapat mengunjungi pada laman ini 🔗
[[oh-my-posh]](https://ohmyposh.dev/docs/installation/windows)

```
  winget install JanDeDobbeleer.OhMyPosh -s winget
```

dan lakukan update untuk memastikan ter-install yang terbaru

```
  winget upgrade JanDeDobbeleer.OhMyPosh -s winget
```

## Membuat $PROFILE

Masuk dalam powershell dan silahkan input prompt

```
notepad $PROFILE
```

buka pada file **$PROFILE** diatas dan silahkan copy isinya, lalu simpan

Untuk reload $PROFILE ketikkan:

```
. $PROFILE
```

## Konfigurasi setting CMD

masuk pada setting.json pada cmd lalu copy file **setting** diatas, simpan semua dan refresh _powershell_
setting bisa dilakukan di setting pada _powershell_ (ctrl+shift+,) dan pilih open JSON File
