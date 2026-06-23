<div align="center">

#  ff-dots

**fastfetch config buat terminal yang ga norak tapi tetep keren**

![License](https://img.shields.io/github/license/nez4rt/ff-dots?style=flat-square&color=yellow)
![Last Commit](https://img.shields.io/github/last-commit/nez4rt/ff-dots?style=flat-square&color=green)
![Stars](https://img.shields.io/github/stars/nez4rt/ff-dots?style=flat-square&color=cyan)

</div>

---

## ✦ preview

> *marin kita di sebelah kiri, info sistem di sebelah kanan.*

```
                   os    NixOS / Arch / etc
  [marin.png]      ker   7.x.x
                   pkgs  xxx
                   sh    zsh
                   wm    Hyprland
                   up    Xh Xm
                   cpu   Intel / AMD
                   ram   X.X GiB / X.X GiB
                   disk  X.X GiB / X.X GiB

                   󰮯 󰊠 󰊠 󰊠 󰊠 󰊠 󰊠 󰊠
```

---

## ✦ apa aja yang ada di sini

```
ff-dots/
├── config.jsonc     # konfigurasi utama fastfetch
├── gambar/
│   └── marin.png    # waifu sidebar (jangan dihapus pls)
└── LICENSE
```

---

## ✦ cara pakai

**1. clone dulu**
```bash
git clone https://github.com/nez4rt/ff-dots.git
```

**2. copy ke folder config fastfetch**
```bash
cp -r ff-dots/* ~/.config/fastfetch/
```

**3. jalanin**
```bash
fastfetch
```

> **note:** pastiin `marin.png` ada di path `~/.config/fastfetch/gambar/marin.png` biar logo-nya muncul dengan baik.

---

## ✦ requirements

- [`fastfetch`](https://github.com/fastfetch-cli/fastfetch) — tentu aja
- font yang support **Nerd Fonts** (buat icons & color blocks di bawah)
- terminal emulator dengan dukungan warna & unicode

---

## ✦ kustomisasi

Config ada di `config.jsonc`, beberapa hal yang bisa lo tweak:

| key | fungsinya |
|-----|-----------|
| `logo.source` | ganti path gambar sidebar |
| `logo.width / height` | ukuran gambar |
| `keyColor` | warna label tiap modul |
| `modules` | tambahin / hapus info yang ditampilkan |

---

## ✦ modules yang aktif

`os` · `kernel` · `packages` · `shell` · `wm` · `uptime` · `cpu` · `memory` · `disk` · `color-blocks`

---

## ✦ license

MIT — bebas dipake, dimodif, dishare. credit mah optional tapi appreciated 🙏

---

<div align="center">
<sub>made with ♥ by <a href="https://github.com/nez4rt">nez4rt</a></sub>
</div>
