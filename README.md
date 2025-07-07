# Phasmophobia Evidence Tracker for OBS

A sleek, interactive Phasmophobia Evidence Tracker designed specifically for streamers! Track evidence in real-time with dramatic fullscreen alerts that engage your viewers.

## ✨ Features

- **🎯 Interactive Evidence Tracking** - Left-click to confirm evidence, right-click to rule out
- **🎬 Dramatic Fullscreen Alerts** - Eye-catching animations when evidence is found
- **👻 Real-time Ghost Elimination** - Shows remaining possible ghosts as you gather evidence
- **📺 Stream-Optimized Design** - Compact bottom-left panel that doesn't block gameplay
- **🎮 OBS Integration** - Works seamlessly with OBS Browser Source interaction
- **📱 Viewer-Friendly** - Large, readable text

![Demonstration](https://github.com/LindenSec/PhasmophobiaEvidenceTracker/blob/main/Demo.gif)

## 🚀 Quick Setup

### 1. Download & Add to OBS
1. Download the `.html` file from this repository
2. In OBS: **Sources** → **Add** → **Browser Source**
3. Set the **URL** to your downloaded file path: `file:///path/to/tracker.html`
4. Configure dimensions:
   - **Width**: 2560
   - **Height**: 1440
   - ✅ Check **"Interact"**

### 2. Position for Streaming
- The tracker appears in the **bottom-left corner**
- **Right-click** the Browser Source → **Interact** to control during gameplay
- Position the interact window on your **second monitor** for easy access

## 🎮 How to Use

| Action | Result |
|--------|--------|
| **Left Click** | ✅ Confirm evidence + trigger fullscreen alert |
| **Right Click** | ❌ Rule out evidence (quiet) |
| **Middle Click** | 🔄 Reset individual evidence to unknown |
| **Reset Button** | 🆕 Clear all evidence |

## 📊 What Viewers See

### Normal View
- Compact evidence tracker in bottom-left
- Real-time ghost count updates
- Visual confirmation of found/ruled-out evidence

### Evidence Found Alert
- **Massive fullscreen announcement**: "EMF LEVEL 5 HAS BEEN FOUND"
- **Ghost count**: "3 POSSIBLE GHOSTS"
- **Remaining suspects**: "Spirit • Wraith • Myling"
- **Special message**: "GHOST FOUND" when narrowed to one suspect

## ⚙️ Customization

### Resolution Settings
The tracker is optimized for **1440p (2560x1440)**. To change resolution:

1. Open the `.html` file in a text editor
2. Find `.alert-overlay` in the CSS section
3. Update dimensions:
```css
.alert-overlay {
    width: YOUR_WIDTH;    /* e.g., 1920px for 1080p */
    height: YOUR_HEIGHT;  /* e.g., 1080px for 1080p */
}
```
## 💜 Support the Developer

Enjoying this tracker? Follow me on Twitch for live Phasmophobia streams where I use this tracker!

**[🎮 twitch.tv/incredicate](https://twitch.tv/incredicate)**
**[✖️ x.com/incredicate](https://x.com/Incredicate)**

*See the tracker in action during my ghost hunting adventures!*
