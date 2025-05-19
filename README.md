[![React Native Video Component](https://raw.githubusercontent.com/WiktorNiedzialkowski/react-native-video/master/docs/assets/baners/rnv-banner-bigger.png)](https://thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=banner)

The most battle-tested open-source video player component for React Native - now with support for DRM, offline playback, HLS/DASH streaming, and more.


## 🔍 Features

| Category | Details |
|----------|---------|
| **Universal Format Support** | Native playback on iOS, Android, tvOS & AndroidTV |
| **Streaming Protocols** | HLS, DASH, SmoothStreaming |
| **DRM Support** | Widevine & FairPlay, [Free DRM example stream](https://www.thewidlarzgroup.com/services/free-drm-token-generator-for-video?utm_source=rnv&utm_medium=readme&utm_id=features-drm) |
| **Offline Playback** | Secure downloads, captions, and side-tracks via [Offline SDK](https://docs.thewidlarzgroup.com/offline-sdk?utm_source=rnv&utm_medium=readme&utm_id=features-sdk) |
| **Full Control** | Track selection, events, buffering |
| **Cross‑platform** | Web, Expo, Windows, TV support |



## ✨ Project Status

| Version | State | Architecture |
|---------|-------|--------------|
| **v5 and lower** | ❌ End-of-life [Commercial Support Available](https://www.thewidlarzgroup.com/blog/react-native-video-upgrade-challenges-custom-maintenance-support#how-we-can-help?utm_source=rnv&utm_medium=readme&utm_id=upgradev5) | Old Architecture |
| **v6** | 🛠 Maintained (community + TWG) | Old + New (Interop Layer) |
| **v7** | 🚀 Active Development | Old + New (Full Support) |

v7 introduces full support for the new React Native architecture, unlocking better performance, improved consistency, and modern native modules.

---

## 🚀 Quick Start

```bash
yarn add react-native-video
cd ios && pod install
```

```tsx
import Video from 'react-native-video';

export default () => (
  <Video
    source={{ uri: 'https://www.w3schools.com/html/mov_bbb.mp4' }}
    style={{ width: '100%', aspectRatio: 16 / 9 }}
    controls
  />
);
```

---

## 🧩 Optional Modules


<a href="https://docs.thewidlarzgroup.com/offline-sdk?utm_source=rnv&utm_medium=readme&utm_id=banner"><img src="https://raw.githubusercontent.com/WiktorNiedzialkowski/react-native-video/master/docs/assets/baners/sdk-banner-retina-new.png" alt="Offline SDK Preview"></a> width="40%" align="right" />

### 1 · 📥 Offline SDK

Enable offline streaming with full control over downloads, license lifecycle, secure storage and media access.

- Track selection (bitrate, audio, subtitles)
- Pause / resume & background queueing
- Expiration & auto-cleanup
- Built for Android & iOS
- → [Read the SDK Docs](https://docs.thewidlarzgroup.com/offline-sdk?utm_source=rnv&utm_medium=readme&utm_id=modules-sdk-text)

### 2 · 🧪 Plugin Architecture

Write your own plugins to extend library logic, attach analytics or add custom workflows - **without forking** the core SDK.  
→ [Plugin documentation](https://docs.thewidlarzgroup.com/react-native-video/other/plugin)



## 📚 Documentation & Examples

- 📖 [Full Documentation](https://docs.thewidlarzgroup.com/react-native-video/)
- 📦 [Example: Free DRM Stream](https://www.thewidlarzgroup.com/services/free-drm-token-generator-for-video?utm_source=rnv&utm_medium=readme&utm_id=free-drm)
- 📦 [Example: Offline SDK integration](https://docs.thewidlarzgroup.com/offline-sdk)


## 📰 Community & Media

- 🗽 **React Summit US** – How TWG helped Learnn boost video performance on React Native.  
[Watch the talk »](https://gitnation.com/contents/a-4-year-retrospective-lessons-learned-from-building-a-video-player-from-scratch-with-react-native)

- 🧨 **v7 deep dive** – Why we’re building v7 with the new React Native architecture.  
[Watch on X »](https://x.com/krzysztof_moch/status/1854162551946478051)

- 🛠️ **How to maintain OSS** – Bartłomiej’s talk from the Warsaw meetup.  
[Watch here »](#)

- 📺 **React Native on the Big Screen** – Bartłomiej on panel about scaling RN for TV.  
[Watch here »](#)


## 💼 TWG Services & Products

| Offering | Description |
|----------|-------------|
| [**Professional Support Packages**](https://www.thewidlarzgroup.com/issue-boost?utm_source=rnv&utm_medium=readme&utm_campaign=professional-support-packages#Contact) | Priority bug-fixes, guaranteed SLAs, roadmap influence |
| [**Issue Booster**](https://www.thewidlarzgroup.com/issue-boost?utm_source=rnv&utm_medium=readme) | Pay‑per‑issue fast‑track for urgent fixes |
| [**Offline Video SDK**](https://www.thewidlarzgroup.com/offline-video-sdk/?utm_source=rnv&utm_medium=readme&utm_campaign=downloading&utm_id=offline-video-sdk-link) | Plug‑and‑play secure download solution for iOS & Android |
| [**Integration Support**](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_campaign=integration-support#Contact) | Hands‑on help integrating video, DRM & offline into your app |
| [**Free DRM Token Generator**](https://www.thewidlarzgroup.com/services/free-drm-token-generator-for-video?utm_source=rnv&utm_medium=readme&utm_id=free-drm) | Generate Widevine / FairPlay tokens for testing |
| [**Ready Boilerplates**](https://www.thewidlarzgroup.com/showcases?utm_source=rnv&utm_medium=readme) | Ready apps with background uploads, Offline HLS/DASH DRM, Video Frames Scrubbing, TikTok video roll, Frame Processor with Skia |
| [**React Native Video Upgrade Guide**](https://www.thewidlarzgroup.com/blog/react-native-video-upgrade-challenges-custom-maintenance-support?utm_source=rnv&utm_medium=readme&utm_id=upgrade-blog&utm_campaign=v7) | Common upgrade pitfalls & how to solve them |

*See how [TWG](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=services-text) helped **Learnn** ship a world‑class player in record time -  [case study](https://gitnation.com/contents/a-4-year-retrospective-lessons-learned-from-building-a-video-player-from-scratch-with-react-native).*


## 🌍 Stay Connected

- 💬 [Join the Discord](https://discord.gg/9WPq6Yx)
- 🐦 [Follow on X / Twitter](https://x.com/TheWidlarzGroup)
- 💼 [TWG on LinkedIn](https://linkedin.com/company/the-widlarz-group)

## 🏢 Adopters

Following is a partial list of companies happily using react-native-video in production to craft applications.  
Want to see your company here? [Submit a PR!](https://github.com/react-native-video/react-native-video)

- [Discord](https://discord.com)
- [LesMills](https://www.lesmills.com)
- [Amazon](https://www.amazon.com)
