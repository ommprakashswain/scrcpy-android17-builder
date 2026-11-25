# 🖥️ scrcpy Android Desktop for Windows (Android 17 Fix)

![Windows](https://img.shields.io/badge/Windows-x64-0078D4?logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-17%2B-3DDC84?logo=android&logoColor=white)
![Unofficial](https://img.shields.io/badge/build-unofficial-orange)

**Run your phone's Android Desktop on your Windows PC. One download, one double-click.** 🚀

Fixes scrcpy `--new-display` on Android 17: taskbar and launcher icons showing but apps not opening in Android Desktop mode.

<p align="center">
  <img width="32%" alt="Android desktop screenshot 1" src="https://github.com/user-attachments/assets/04a41164-6145-43eb-96c2-14164ba49964" />
  <img width="32%" alt="Android desktop screenshot 2" src="https://github.com/user-attachments/assets/ec96e29d-c046-4e4b-8422-e96bad2103f9" />
  <img width="32%" alt="Android desktop screenshot 3" src="https://github.com/user-attachments/assets/e7f4d530-3fe1-4dd3-8cc5-96aff5e58487" />
</p>

---

## ⬇️ Download

### 👉 [**Get the latest release**](https://github.com/ommprakashswain/scrcpy-android17-builder/releases/latest)

Download `scrcpy-win64-v5.0.1-android17-fix.zip`, unzip it, and double-click **`Start-Android-Desktop`**.

Full step-by-step instructions are on the release page.

---

## 🔧 What this is

- Official **scrcpy v5.0.1** for Windows.
- Only `scrcpy-server` (the part on the phone) is rebuilt with a ~10-line fix.
- Patch source: [Genymobile/scrcpy PR #7127](https://github.com/Genymobile/scrcpy/pull/7127) (not merged upstream yet).
- Exact diff: [`android17-new-display-fix.patch`](android17-new-display-fix.patch)
- Built by [GitHub Actions](../../actions) from the official tag, so you can check it or build your own: open **Actions → Run workflow**.

**Needs:** Windows, a phone on **Android 17 or newer**, and USB debugging on.

---

## 🙏 Credits

[scrcpy](https://github.com/Genymobile/scrcpy) by Genymobile (Apache 2.0). Launcher and packaging by [@ommprakashswain](https://github.com/ommprakashswain).

> ⚠️ **Unofficial build. Not affiliated with or endorsed by Genymobile.**
