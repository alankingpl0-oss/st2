# MSKI26

<a href="http://www.maksoft.kolejopedia.pl/st/html">
  <img src="https://img.shields.io/badge/Graj-PowerKilo--blue?style=plastic&icon=github" width="200" alt="Pobierz">
</a>

<br></br>

---

**Maksoft Symulator Kuriera Interplanetarnego 2026** to nowoczesna odsłona klasycznej gry Space Travel z 1969 roku. MSKI26 działa w przeglądarce.

## Sterowanie
| Klawisz | Akcja
|---------|---------------|
| W       | Ruch do przodu|
| S       | Wsteczny|
| E/Q     | Skala|
| A       | Obrót w lewo|
| D       | Obrót w prawo|
| 1       | Zakończ grę|
| 2       | Odródź się|

## Gra

Gra sama w sobie jest bardzo, bardzo trudna. Dla kogoś, kto nigdy nie zrozumiał grawitacji, zalecamy natychmiastowe naciśnięcie kombinacji Alt-F4/Cmd-F4.

## Fabuła
...a raczej jej brak.

Pojawiamy się na Ziemi. Dostajemy zlecenie, żeby przewieść np. zapasy lukrecji z naszej planety np. do Saturna, czy Jowisza. Gra obsługuje 32 ciała niebieskie, jednak na tylko kilku dostępne są bazy, do których dostarczamy/zabieramy różne niebezpieczne ładunki.

Lecimy zatem z Ziemi do Jowisza. Lądujemy ostrożnie, bardzo ostrożnie, żeby się nie rozwalić koncertowo. Jeżeli wylądowaliśmy na Jowiszu (tak... na Jowiszu w MSKI26 można lądować), pojawi się nam zlecenie, a jeżeli nie, próbujemy podchodzić do manewru lądowania.

Zlecenie może kazać nam polecieć z ładunkiem (np. paliwem nuklearnym) na Ziemię lub Księżyc. W grze została zaimplementowana bardzo realistyczna mechanika grawitacji ciał niebieskich, np. Księżyć przyciąga nas bardzo słabo, z kolei Ziemia przyciąga nas z naturalną siłą grawitacji (dokładniej $9,62\text{ m/s}^2$).



<!--


This is a C port of Ken Thompson's
[Space Travel](https://en.wikipedia.org/wiki/Space_Travel_\(video_game\)),
ported from PDP-7 assembly. The original source files are in `src/cmd/st*.s`
in the [pdp7-unix](https://github.com/DoctorWkt/pdp7-unix) repository. The game
is available to [play online](https://akr.am/st) via WebAssembly.

## Install

The SDL3 library is required.

Run `make` to build `st`.

Run `make install` to install to `/usr/local/bin`.

Run `make wasm` (requires [Emscripten](https://emscripten.org)) to build a
WebAssembly version of the game. To play it, launch a web server via
`python3 -m http.server -d html` and go to http://localhost:8000.

## Controls

| Key | Action       |
|-----|--------------|
| 1   | Quit         |
| 2   | New game     |
| 3   | Thrust down  |
| 4   | Thrust up    |
| 5   | Yaw right    |
| 6   | Yaw left     |
| 7   | Scale up     |
| 8   | Scale down   |

You can also use the arrow keys for yaw and scale.

## Gameplay

> For controls, there were several buttons: jet forward, jet back, turn left,
> turn right; go up scale on the display, go down scale. The acceleration of
> the ship was fixed, but it scaled with the display scale--it was thus fixed
> in terms of pixels/sec/sec. Normally the ship was in the center of the screen
> and always pointed up; the display showed the plan view of the solar system,
> so that the "rotate" controls rotated the solar system around you on the
> display.
>
> No relativity; scale up enough and you travel to Pluto in a few seconds. But
> don't scale up too much, or you might not find the Solar System again without
> restarting.
>
> The object of the game was simply to fly around, get into orbits, land.
> "Land" meant to cross the surface with a small enough speed.
>
> *[Space Travel: Exploring the solar system and the
> PDP-7](https://www.bell-labs.com/usr/dmr/www/spacetravel.html) by Dennis
> Ritchie*



The current dominating attractor, scale, and landing status (L/CL for
landed/crash landed) are displayed at the bottom. The moving dot on the line
below the main view represents the horizontal velocity relative to the current
dominating attractor.
-->
