<div>
<h1>A fan project containing mods for Dota 2 customization</h1>

  <p>
    <a href="">
      <img src="https://custom-icon-badges.demolab.com/badge/Website-404040?style=for-the-badge&logo=globe&logoColor=white" alt="Website">
  </p>
</div>

---

 ## What is D2Mods?

**D2Mods** This is a Dota 2 mod repository that provides players with visual customization for the game. Browse and download custom mods.

---

## Installation Guide

### Quick Start

1. Download the `.vpk` file(s) you want
2. Create the folder `dota_123` inside: `Steam\steamapps\common\dota 2 beta\game\`
3. Place your downloaded mods into that folder
4. Add `-language 123` to Dota 2 launch options in Steam

> **Using multiple mods?** If file names conflict, rename duplicates to `pakXX_dir.vpk` (e.g. `pak10_dir.vpk`, `pak11_dir.vpk`, ...). Alternatively, use **[VPKMerge](https://h6rd.github.io/Dota2PornFxWeb/?category=tools&mod=VPKMerge+-+Combine+VPKs)** to combine them into a single file.

> **Using Minify?** Place mods in the `dota_minify` folder and add `-language minify` to launch options instead.

---

<details>
<summary><b>🇷🇺 Инструкция по установке (Russian)</b></summary>

<br>

1. Скачайте нужный файл `.vpk`
2. Поместите его в нужную папку:

**Для русского языка** — используйте папку `dota_russian`:
```
Steam\steamapps\common\dota 2 beta\game\dota_russian\
```
Добавьте в параметры запуска: `-language russian`

**Для английского языка** — создайте папку `dota_123`:
```
Steam\steamapps\common\dota 2 beta\game\dota_123\
```
Добавьте в параметры запуска: `-language 123`

**Если используете Minify** — положите моды в папку `dota_minify` и добавьте `-language minify`

> **Важно:** Если имена файлов совпадают, переименуйте повторяющийся в `pakXX_dir.vpk`, где XX — 10, 11, 12... 99.
> Для объединения нескольких модов в один файл используйте **[VPKMerge](https://h6rd.github.io/Dota2PornFxWeb/?category=tools&mod=VPKMerge+-+Combine+VPKs)**.

</details>

---

## Tools & Utilities

| Tool | Description |
|------|-------------|
| [**VPKTool**](https://h6rd.github.io/Dota2PornFxWeb/?category=tools&mod=VPKTool+-+Extract+%26+Pack+VPKs) | Extract and repack VPK archives |
| [**VPKMerge**](https://h6rd.github.io/Dota2PornFxWeb/?category=tools&mod=VPKMerge+-+Combine+VPKs) | Merge multiple VPK files into one |
| [**Compiler**](https://h6rd.github.io/Dota2PornFxWeb/?category=tools&mod=Compiler) | Compile `.vtex_c`, `.vpcf_c`, `.vsnd_c`, `.vxml_c`, `.vcss_c` assets |

---

## Troubleshooting

<details>
<summary><b>Mod doesn't work after installation</b></summary>

<br>

To check whether the issue is with the mod itself or your installation:

1. Create a folder named `dota_test` inside `steamapps\common\dota 2 beta\game\`
2. Place the mod there and set launch options to `-language test`
3. Launch the game and check:
   - ✅ Works? → The original installation had an issue. Re-check your language folder and reinstall.
   - ❌ Still broken? → The mod itself is the problem.

</details>

<details>
<summary><b>Merged mods cause issues</b></summary>

<br>

Try installing the problematic mod separately, outside of the merged pack. Some mods conflict at the file level when combined.

</details>

<details>
<summary><b>Background replacement issues</b></summary>

<br>

- The video must be **30 seconds or shorter**
- File format must be **`.webm`**
- **"An error occurred during playback"** → Try a different source video
- **"Background doesn't change"** → Follow the general troubleshooting steps above

</details>

<details>
<summary><b>Emblems not visible</b></summary>

<br>

Open the in-game console and run:
```
r_draw_selected_ring 1
```

Also make sure you are not using the **Misc Optimization** mod from Minify, as it disables standard emblem rendering.

</details>

---

## Credits

Content is sourced from the Dota 2 modding community. Original sources include:

- [**Dota2Changer**](https://dota2changer.com/)
- [**MOR**](https://vk.com/amir4anmods)

---

## Libraries Used

| Library | Purpose |
|---------|---------|
| [zip.js](https://github.com/gildas-lormeau/zip.js/) | ZIP read/write in the browser |
| [lz-string](https://github.com/pieroxy/lz-string) | LZ-based string compression |
| [m3e](https://github.com/matraic/m3e) | Material 3 Expressive UI components |

---

## ⚠️ Disclaimer

Modifying game files is done **entirely at your own risk**. In the event of a ban or other consequences, responsibility lies solely with the user. This project is not affiliated with Valve Corporation or Dota 2.

## License

Contents of this repository are licensed under [GPL-3.0](LICENSE).

<!--
**D2Mods/D2Mods** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
