# 🎨 Helix Open Source Themes by gokayburuc

This repository contains various **themes** for the [Helix Editor](https://helix-editor.com), each carefully crafted to provide a beautiful and readable editing experience.

---

## 📁 Theme Index

- [Murmur](./murmur.toml) — A soft, pastel-toned custom theme.
- [Solarized Osaka](./solarized-osaka.toml) — A variant of Solarized with Osaka-inspired hues.
- [NightWolf](./nightwolf.toml) - AMOLED theme for NightWolves
- [LowEyeStrain](./low-eye-strain.toml) - Low Eye Strain Theme For Night Owls
- [NeonCity](./neon-city.toml) - Neon City Theme for Synthwave Lovers
---

## Screenshots

Murmur:

![Murmur-ss](./img/murmur-ss.png)

Solarized Osaka:

![Solarized-Osaka](./img/solarized-osaka-ss.png)

NightWolf:

![NightWolf](./img/nightwolf.png)

LowEyeStrain:

![LowEyeStrain](./img/low-eye-strain.png)

NeonCity:

![NeonCity](./img/neon-city.png)


## 🚀 Usage

To use one of these themes in Helix:

1. Copy the desired theme file (e.g. `murmur.toml`) into your Helix themes directory:

   ```bash
   cp murmur.toml ~/.config/helix/themes/
   ```

2. Open Helix and apply the theme with the `:theme` command:

   ```helix
   :theme murmur
   ```

3. To set it as the **default theme**, add the following to your `~/.config/helix/config.toml`:

   ```toml
   theme = "murmur"
   ```

---

## 🌈 Transparent Themes

To create a **transparent** version of any theme:

1. Create a new file in your Helix themes directory, e.g. `murmur-transparent.toml`.
2. Paste the following content:

   ```toml
   inherits = "murmur"

   [ui.background]
   ```

This overrides the background to be transparent while keeping the rest of the theme intact.

---

## 🧊 Contributing

Feel free to fork the repo and create your own themes or submit pull requests to contribute!
If you create your own transparent variant or custom theme, feel free to share it back.
