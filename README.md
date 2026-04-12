<p align="center">
    <img src="RESOURCES/Invizimals.png" width="400" height="auto" alt="Invizimals title" class="title">
    <br><img alt="Dynamic JSON Badge" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FUbeJelly%2FInvizimals_Project_Catalog%2Frefs%2Fheads%2Fmain%2Finvizimals.json&query=%24.catalog.total_cards&style=flat&label=Total%20cards%20recorded&labelColor=%23bc45e3&color=%23d1ff51&cacheSeconds=10800">
</p>

# 🌌 Invizimals: Project Catalog

**Welcome to Invizimals Universe!**  
This is a project by the community and for the community, which revives the Invizimals saga on the web with a modern, interactive style.

<p align="center">
    <video src="https://github.com/user-attachments/assets/29275648-aa6e-410b-a92b-92d3be141f0c" width="640" height="360" controls></video>
</p>

---

## 🎮 Description

This project is an **interactive encyclopedia of cards** from the generations:

1. **Hidden Challenges**  
2. **New Alliance** (coming soon)
3. **PSP cards** (coming soon)

Main features:

- For now, you'll find the **Hidden Challenges** cards of the Fire element.
- The cards will become changed over time.
- Steam trading cards inspired hover effects!
- Invizimals: Shadow Zone inspired theme!

---

## 💾 Data Structure
```JSONC
{
    // JSON data of entire catalog
    "catalog": {
        "total_cards": 91,
        "total_types": [
            {
                "type": "fire",
                "total": 44
            },
            ...
        ]
    },

    // Series has its own array of Invizimals
    "series": {
        "Hidden_Challenges": [
            {
                "id": 1,
                "name": "Beatwidow",
                "type": "Fire / PUP / 001",
                "image": "SERIES/INVIZIMALS_HIDDEN_CHALLENGES/TYPES/FIRE/ART/01/frontal.png",
                "image2": "SERIES/INVIZIMALS_HIDDEN_CHALLENGES/TYPES/FIRE/ART/01/personaje.png",
                "arImage": "SERIES/INVIZIMALS_HIDDEN_CHALLENGES/TYPES/FIRE/ART/01/ar.png",
                "description": "A dancing spider? This Invizimal world is full of surprises! I present Beatwidow, the queen of the disco, who can break dance or as a robot... Whatever you want!! This creature is such a good dancer that she has a disco ball in her stomach. By the way, watch that ball... maybe you can use it in more... dangerous ways!",
                "stat": "285 / 150",
                "habitats": "FIRE"
            },
            ...
        ]
    }
}
```

## 📁 Project Structure

```bash
root
├── index.html ← Invizimals visuals
├── invizimals.json ← The Invizimals data that index.html reads.
│
└── SERIES
  ├── INVIZIMALS
  ├── INVIZIMALS: SHADOW ZONE
  ├── INVIZIMALS: HIDDEN CHALLENGES
  │ └── TYPES
  │   ├── FIRE/
  │   │   ├── ART/ ← Individual images for Invizimals and AR cards.
  │   │   └── PDF/ ← Compiled cards in PDF format.
  │   ├── ICE/
  │   ├── JUNGLE/
  │   ├── ...
  └── ...

```
## 🌟 Next Steps

- Add all the Invizimals of other elements in **Hidden Challenges**.
- Build filters that will allow you to select an element in order to view cards that interest you.
- Build a search engine to filter by the name of each **Invizimals**.
- Add other Invizimals from other series.

## 👥 Credits
- Cards by [u/HeavyEquivalent479](https://www.reddit.com/user/HeavyEquivalent479/), see [Drive](https://drive.google.com/drive/folders/1GnVYD49PDrJ74yKlt0Vd2FLydV79ETov)
- Card data reference from [u/Organic_Woodpecker64](https://www.reddit.com/user/Organic_Woodpecker64/), see [Spreadsheet](https://onedrive.live.com/:x:/g/personal/DD980C6F23226519/EXIzvOUrS0RHhmyvIVfMb6wBiBmZzQUIT1Fjm6vszJdMqg?resid=DD980C6F23226519!se5bc33724b2b4744866caf2157cc6fac&ithint=file%2Cxlsx&e=noYxr9&migratedtospo=true&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3gvYy9kZDk4MGM2ZjIzMjI2NTE5L0VYSXp2T1VyUzBSSGhteXZJVmZNYjZ3QmlCbVp6UVVJVDFGam02dnN6SmRNcWc_ZT1ub1l4cjk)
- Project started by [r4nc0x](https://github.com/r4nc0x), see [Repository](https://github.com/r4nc0x/proyecto_Invizimals)
- The rest of Ice Invizimal cutouts and some Fire types were edited by me (Jelly).

## 📌 License

This project is **free for personal and community use and modification,** provided that the source and community are cited.

Do not sell without permission from the authors, that is, our friends at **PANINI** and the creators of the **INVIZIMALS** saga.

Orbitron font, Copyright 2018 The Orbitron Project Authors: [Open Font License](RESOURCES/Fonts/Orbitron/OFL.txt)

---
This is free to use and modify however you want for personal projects, but don't use it for any monetary gain.

This project and its contents are not affiliated with, endorsed by, and/or maintained by **Sony Computer Entertainment America LLC**, **Novarama**, nor **PANINI**.

All rights reserved of the original, unedited files and properties of Invizimals to its legal creators and owners.