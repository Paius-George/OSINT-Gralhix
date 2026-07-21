# 🔍 OSINT Exercises — Solutions

*[Versiunea în limba română →](README.ro.md)*

> My written solutions to the **OSINT exercises** published by Sofia Santos on
> [gralhix.com](https://gralhix.com/list-of-osint-exercises/) — a series of
> open-source intelligence challenges covering geolocation, chronolocation,
> reverse image search, and information verification.

Each exercise starts from a single piece of media — a photo, a screenshot, a
newspaper clipping, or a video — and asks you to extract the truth hidden inside
it using only public sources. This repository documents my full reasoning for
each one, step by step, with the images and tools I used along the way.

Every writeup is available in **English** (main) and **Romanian** (`README.ro.md`
inside each folder).

---

## 🧭 The exercises

| # | Challenge | Skills exercised |
| :--: | --- | --- |
| [**001**](%23001/README.md) | Geolocate the exact spot a Twitter photo was taken (Kiffa, Mauritania) | Geolocation · Google Earth · shadow/terrain analysis |
| [**002**](%23002/README.md) | Identify a train station and the name + height of the tallest structure in view (Melbourne) | Geolocation · landmark ID · satellite view |
| [**003**](%23003/README.md) | Name the building and coordinates of a presidential visit (Ankara, Turkey) | Reverse image search · reflection analysis |
| [**004**](%23004/README.md) | Find an island resort's name, coordinates, and camera direction (Chuuk, Micronesia) | Reverse image search · geolocation · orientation |
| [**005**](%23005/README.md) | Locate polar bears on a zoo live-cam, plus the temperature at capture time (San Diego) | Reverse image search · chronolocation · weather history |
| [**006**](%23006/README.md) | Verify whether a viral news photo is real or fake | Image verification · misinformation debunking |
| [**007**](%23007/README.md) | Determine the place, year, and a poster's URL from an old mall photo (Lisbon) | Geolocation · chronolocation · historical imagery |
| [**008**](%23008/README.md) | Read a Chinese newspaper page to find who, when, and where (Norfolk, Virginia) | Foreign-language OCR · translation · venue ID |
| [**009**](%23009/README.md) | Find a video's post time and the coordinates of the walk (Tirana, Albania) | Account pivoting · video geolocation · traffic/terrain |
| [**010**](%23010/README.md) | Attribute event photos to a photographer and trace their prior city (Benin) | Google Lens · attribution · Wayback Machine |

---

## 🛠️ Tools used across the exercises

- **Search & pivoting:** Google, Yandex, Bing
- **Reverse image search:** Yandex Images, TinEye, Google Lens
- **Mapping & imagery:** Google Maps, Google Street View, Google Earth (incl. historical imagery)
- **Archival:** Wayback Machine (archive.org)
- **Verification:** Wikipedia, source cross-checking, weather history, EXIF/context clues

---

## 🙏 Credits

The exercises are created by **Sofia Santos (Gralhix)** and published at
[gralhix.com/list-of-osint-exercises](https://gralhix.com/list-of-osint-exercises/).
This repository contains only my own solutions and commentary — all credit for
the challenges themselves goes to the original author.
