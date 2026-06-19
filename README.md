# Grounded
super duper repository with Grounded 1 and 2 saves

repositorio com saves do Grounded 1 e 2


# Fake time (linux)

Very useful to get event items / muito util pra pegar itens de evento

Arch ```sudo pacman -Syu libfaketime```

Debian/Ubuntu ```sudo apt install faketime```

Fedora ```sudo dnf install libfaketime```

# Steam parameter

```LD_PRELOAD=/usr/lib/libfaketime.so.1 FAKETIME="2026-12-13 12:59:59" %command%```

or

```LIB_PATH=$(find /usr/lib* -name "libfaketime.so.1" -print -quit) LD_PRELOAD="$LIB_PATH" FAKETIME="2026-12-13 12:59:59" %command%```

[RunAsDate (Windows)](https://www.nirsoft.net/utils/run_as_date.html)

