# Score Tracker

___Application for tracking player scores in card and board games___

Score Tracker is an application for tracking player scores in card and board games. It also contains additional functionality such as timer for measuring players turn times.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub io.github.weclaw1.ScoreTracker
flatpak run io.github.weclaw1.ScoreTracker
```

## Building

```
git clone git@github.com:flathub/io.github.weclaw1.ScoreTracker.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.weclaw1.ScoreTracker.yaml
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Python
