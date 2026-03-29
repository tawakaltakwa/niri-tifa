# Niri Tifa

Konfigurasi niri sederhana bertema warna dan wallpaper Tifa. Semua konfigurasi berdasarkan kebutuhan dan kebiasaan personal, kalau ada yang nyasak ke sini dan mau pake juga silahkan, edit saja sendiri bagian yang kurang sesuai dengan kebutuhan kalian.

## Screenshot

### Desktop
Tifa dan Aerith nyari tumpangan. Tentu saja cuma wallpaper yang bisa diganti.
<br>
![Screenshot](screenshot/Screenshot1.png)

### Menu 1 - Aplikasi Launcher
Menggunakan wofi.
<br>
![Screenshot](screenshot/menu1-wofi.png)

### Menu 2 - Umum
Karena kenyataannya windows manager gak ada standar shortcut umum, custom semua, jadi bisa saja lupa shortcutnya, apalagi kalau baru pertama kali coba pakai WM, atau sekian waktu gak buka Komputer, makanya dibuat menu ini, memang sih niri ada show up shortcut pas awal di buka, tapi saat itu ke tutup belum ke hapal semua kadang bingung mau pencet apa buat nampilin itu lagi, ya namanya belum ke hapal/ kebaca semua, dan saya kena istilah `SKILL ISSUE` di banyak hal. Jadi intinya biar bagian topbar bisa beroperasi hanya dengan klik mirip DE.
<br>
![Screenshot](screenshot/menu2-custom.png)

### Menu 3 - System Poweroff/Shutdown
untuk Shutdown, Restart, dll.
<br>
![Screenshot](screenshot/menu3-custom.png)

### Jam Sunda
Cuma gimik nama istilah jam dalam bahasa Sunda untuk tiap jamnya, yang di Sundanya sendiri mulai jarang digunakan. Beda daerah Sunda bisa beda varian referensi.
<br>
Link [JamSunda](https://github.com/tawakaltakwa/JamSunda), btw yang jamsunda2.sh (versi referensi 2) ada sedikit error script tampilan yang tak kunjung saya dibenerin sampai sekarang. Jadi gunakan yang jamsunda.sh saja atau benerin sendiri.
<br>
![Screenshot](screenshot/jam-sunda.png)

## Shortcut
Untuk launch aplikasi dipisah pake ALT. kebanyakan control umum masih default niri.

| Keyboard | Fungsi |
| --- | --- |
| ALT+SPACE | Open app launcher: wofi |
| ALT+B | Open browser |
| ALT+L | Lock screen: gtklock |
| ALT+R | Command runner: wmenu |
| ALT+E | File manager: nemo |
| ALT+T | Terminal: alacritty |
| MOD+Return (Enter) | Terminal: alacritty (juga)|
| ALT+Escape | Task Manager: Resources |
| MOD+F | Maximize window |
| MOD+SHIFT+F | Fullscreen |
| MOD+SHIFT+1 | Screenshot Selection |
| MOD+SHIFT+2 | Screenshot Fullscreen |
| MOD+SHIFT+3 | Screenshot Window |
| MOD+Q | Tutup window |
| MOD+BACKSPACE | Tutup window (juga) |

nemu duplikat shortcut? Emang duplikat, pernah nyoba beberapa WM, pernah membiasakan diri ngikutin shortcut default tutup window pake MOD+Q dan pernah juga membiasakan diri dengan MOD+Backspace, jadi ya biar kondisional refrek jari kebiasaan lamanya ke yang mana pun tetap operasional. Lagipula gak bikin eror system, jadi boleh kan...
<br>
<br>
Folder hasil screenshot di ~/Pictures/Screenshots

## Instalasi / Konfigurasi

Gak ada script auto installer, jadi kalau mau pakai ya copy paste saja folder dan isinya ke `~/.config/`.
<br>
<br>
3 folder ini yang perlu di copy paste:<br>
![Screenshot](screenshot/3folder.png)
<br>
<br>
Kemudian install aplikasi di bawah.

## Aplikasi yang digunakan

- niri
- waybar
- waybar-niri-taskbar
- swaybg
- gtklock
- wofi
- mako
- fastfetch
- wmenu
- alacritty
- nemo
- nemo-fileroller
- nm-applet / network-manager-applet
- xwayland-satellite
- polkit-gnome
- capitaine-cursors
- resources
- celestial-gtk-theme (yang warna merah)
- flat-remix (ikon)
- nwg-look (untuk milih tema gtk, ikon, cursor, dll)

## Catatan

open terminal nemo defaultnya gnome-terminal, untuk gantinya bisa di setting pake deconf-editor.
<br>
![Screenshot](screenshot/nemo-terminal.png)