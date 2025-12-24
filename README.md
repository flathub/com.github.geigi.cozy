# Cozy

___Listen to audio books___

Do you like audio books? Then lets get cozy!

Cozy is a audio book player. Here are some of the features:

- Import all your audio books into Cozy to browse them comfortably
- Listen to your DRM free mp3, m4b, m4a (aac, ALAC, …), flac, ogg and wav audio books
- Remembers your playback position
- Sleep timer
- Playback speed control for each book individually
- Search your library
- Multiple storage location support
- Offline Mode! This allows you to keep an audio book on your internal storage if you store your audio books on an external or network drive. Perfect to listen to on the go!
- Drag and Drop to import new audio books
- Sort your audio books by author, reader and name

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub com.github.geigi.cozy
flatpak run com.github.geigi.cozy
```

## Building

```
git clone git@github.com:flathub/com.github.geigi.cozy.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.github.geigi.cozy.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Python
