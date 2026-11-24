# Hyperfocus — Mac nie zaśnie, a Teams nie pokaże „nieaktywny”

Hyperfocus to mała aplikacja w pasku menu z dwoma przełącznikami:

- **FOCUS — ekran nie gaśnie.** Mac nie usypia ekranu, nie włącza wygaszacza ani blokady. Bez żadnych zgód.
- **HYPER — status aktywny.** Gdy przez chwilę nic nie robisz, Hyperfocus zeruje systemowy licznik bezczynności — Microsoft Teams zostaje zielony. Na macOS 27 bez ruszania kursora i bez żadnych zgód; jeśli na twoim macOS to nie zadziała, aplikacja poprosi o zgodę w Ustawieniach → Prywatność i przesunie kursor o jeden punkt. Sprawdzone w Teams; w innych komunikatorach może nie działać.
- **Czas** — bez końca, 15/30/45 minut, 1/2/4/8 godzin, dopóki działa wybrana aplikacja albo dopóki trwa pobieranie (Safari, Chrome, Edge, Firefox, Opera).
- **Zablokowany ekran** — gdy zablokujesz Maca, sygnał HYPER się wstrzymuje i ekran może zgasnąć; po odblokowaniu wszystko wraca samo.
- **Sygnał po bezczynności** — co 30 s, 1, 2 albo 4 minuty bez ruchu.

Po polsku i po angielsku, aktualizuje się sam.

## Ustawienia

Sekcja „Ustawienia” w okienku (podświetlone kółko = włączone):

- **Kolor podświetlenia** — domyślnie biały; do wyboru czerwony, pomarańczowy, żółty, zielony, niebieski, indygo albo różowy. Wybrany kolor mają przełączniki, wybrane przyciski i kreski.
- **Ciemne szkło** — okienko ciemne jak menu systemu, nawet na jasnej tapecie (bez tej opcji szkło przejmuje kolory tapety).

- **Pamiętaj ustawienie przełączników** — po uruchomieniu aplikacji FOCUS i HYPER wracają do stanu z ostatniego razu. Razem z Autostartem Hyperfocus działa od razu po włączeniu Maca.
- **Lewy klik włącza i wyłącza** — kliknięcie ikonki w pasku menu od razu włącza albo wyłącza aplikację; okienko otwierasz prawym klikiem (albo z ⌃).
- **Pozwól wygasić ekran** — ekran może zgasnąć, ale Mac nie zaśnie: programy pracują dalej, pobieranie się nie przerwie.
- **Powiadomienia** — informacja, gdy Hyperfocus sam się wyłączy: minął czas, zamknięto wybraną aplikację albo odłączono zasilacz.
- **Włączaj po podłączeniu zasilania** — podłączasz zasilacz, Hyperfocus sam się włącza.
- **Wyłączaj po odłączeniu zasilania** — odłączasz zasilacz, Hyperfocus się wyłącza i nie zjada baterii.
- **Wyłączaj przy baterii poniżej 15%** — na baterii Hyperfocus nie rozładuje laptopa do zera.
- **Godziny pracy** — wybierasz dni i godziny (np. pn–pt 9:00–17:00); na początku Hyperfocus sam się włącza, na końcu wyłącza.

Na dole okienka: **Autostart** (uruchamianie po zalogowaniu), **Aktualizuj**, **Odinstaluj**, **Zakończ**.

## Instalacja

1. Wejdź w [najnowsze wydanie](https://github.com/woreczko/hyperfocus/releases/latest) i pobierz plik **Hyperfocus-….zip** (pozostałych nie potrzebujesz).
2. Rozpakuj go (Safari zwykle robi to samo) i otwórz **Hyperfocus**.
3. Gdy aplikacja zapyta, kliknij **„Przenieś do Programów”**.

Odinstalujesz w okienku: **Odinstaluj…** (sprząta też autostart i zgodę w Dostępności).

**Wymagania:** macOS 14 lub nowszy.

**Prywatność:** Hyperfocus z niczym się nie łączy poza sprawdzaniem aktualizacji na GitHubie. Nie ma własnego serwera i niczego nikomu nie wysyła.

---

# Hyperfocus — your Mac stays awake and Teams never says “away”

Hyperfocus is a small menu bar app with two switches:

- **FOCUS — screen stays on.** Your Mac won't dim the display, start the screen saver or lock. No permissions needed.
- **HYPER — active status.** When you've been idle for a while, Hyperfocus resets the system idle counter, so Microsoft Teams stays green. On macOS 27 it doesn't move the cursor and needs no permissions; if that doesn't work on your macOS, the app asks for access in System Settings → Privacy & Security and moves the cursor by one point. Tested with Teams; other chat apps may not react.
- **Duration** — indefinitely, 15/30/45 minutes, 1/2/4/8 hours, while a chosen app is running, or while downloading (Safari, Chrome, Edge, Firefox, Opera).
- **Locked screen** — when you lock your Mac, the HYPER signal pauses and the display may turn off; it all resumes when you unlock.
- **Signal after idle** — every 30 s, 1, 2 or 4 minutes without movement.

In English and Polish, updates itself.

## Settings

The “Settings” section in the menu (highlighted circle = on):

- **Highlight color** — white by default; or pick red, orange, yellow, green, blue, indigo or pink. Switches, selected buttons and dividers follow it.
- **Dark glass** — a dark menu like the system's, even over a bright wallpaper (without it the glass picks up the wallpaper's colors).

- **Remember last switch settings** — when the app starts, FOCUS and HYPER return to how you left them. With Autostart, Hyperfocus works right after you turn on your Mac.
- **Toggle with left click** — clicking the menu bar icon turns the app on or off right away; open the menu with a right-click (or ⌃-click).
- **Allow display sleep** — the display may turn off, but your Mac won't sleep: apps keep running and downloads keep going.
- **Notifications** — a heads-up when Hyperfocus turns itself off: time is up, the chosen app was closed or the power adapter was unplugged.
- **Activate on power connect** — plug in the power adapter and Hyperfocus turns on.
- **Deactivate on power disconnect** — unplug it and Hyperfocus turns off to save battery.
- **Deactivate below 15% battery** — on battery, Hyperfocus won't drain your laptop to zero.
- **Work hours** — pick days and hours (e.g. Mon–Fri 9:00–17:00); Hyperfocus turns on at the start and off at the end.

At the bottom of the menu: **Autostart** (launch at login), **Update**, **Uninstall**, **Quit**.

## Install

1. Open the [latest release](https://github.com/woreczko/hyperfocus/releases/latest) and download **Hyperfocus-….zip** (you don't need the other files).
2. Unzip it (Safari usually does this for you) and open **Hyperfocus**.
3. When asked, click **“Move to Applications”**.

To uninstall, click **Uninstall…** in the menu (it also removes launch at login and Accessibility access).

**Requirements:** macOS 14 or later.

**Privacy:** Hyperfocus connects to nothing except GitHub to check for updates. It has no server of its own and sends nothing to anyone.
