# NXCODE

Klien AI coding agent NXC: kanvas Monokai seragam, label agent **Build** / **Plan**
berwarna brand, dan kotak prompt input gelap tersendiri.

Jalankan `nxc` di dalam folder proyekmu.

## Instal

### Windows (PowerShell)

buka PowerShell biasa lalu:

```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
iwr -useb https://github.com/nxcodeobject/code/releases/latest/download/install.ps1 | iex
```

Setelah selesai, tutup dan buka lagi terminalnya (PATH termuat ulang), lalu:
`nxc --version` untuk cek.

### Ubuntu / Debian (bash)

```bash
curl -fsSL https://github.com/nxcodeobject/code/releases/latest/download/install | bash
```

Buka terminal baru lalu: `nxc --version`.

## Pemakaian pertama

```bash
cd <folder-proyek>
nxc
```

Tinggal pilih provider/API key lewat perintah `/connect` di dalam sesi.
API key kamu tidak pernah ikut terdistribusi — tersimpan lokal di mesinmu sendiri.

## Persyaratan

- Windows 10/11 x64, atau Ubuntu/Debian x64 (glibc 2.31+, sekitar 20.04 ke atas)
- CPU dengan AVX2 (varian `-baseline` untuk CPU lama menyusul)

## Aset rilis

- `nxc-windows-x64.zip` — Windows, diinstall lewat `install.ps1`
- `nxc-linux-x64.tar.gz` — Linux, diinstall lewat `install`
- `install` / `install.ps1` / `CARA-INSTALL.txt` / `SHA256SUMS`

## Catatan

- Berlisensi MIT.
- NXC adalah proyek pribadi — gunakan dengan bijak.
