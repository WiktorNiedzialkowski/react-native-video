# react-native-video  

<img src="https://raw.githubusercontent.com/WiktorNiedzialkowski/react-native-video/master/docs/assets/baners/rnv-banner-retina.png" href="https://thewidlarzgroup.com?utm_source=rnv&utm_medium=readme&utm_id=banner" alt="React Native Video Component - with DRM (Widevine & FairPlay), HLS, DASH, Offline and Video Download Support" width="100%">

The most battle-tested open-source video player component for React Native, powering apps with 10M+ users.


[![TWG banner](https://img.shields.io/badge/React%20Native%20Experts-TWG-blueviolet?style=for-the-badge)](https://thewidlarzgroup.com?utm_source=rnv&utm_medium=readme&utm_id=badge)

[![npm](https://img.shields.io/npm/v/react-native-video?label=npm&logo=npm)](https://www.npmjs.com/package/react-native-video)
[![CI](https://img.shields.io/github/actions/workflow/status/TheWidlarzGroup/react-native-video/ci.yml?label=CI)](https://github.com/TheWidlarzGroup/react-native-video/actions)
[![Discord](https://img.shields.io/discord/932583855555648562?label=Discord&logo=discord)](https://discord.gg/9WPq6Yx)
[![Twitter Follow](https://img.shields.io/twitter/follow/TheWidlarzGroup?style=social)](https://twitter.com/TheWidlarzGroup)
[![Maintained by TWG](https://img.shields.io/badge/Maintained%20by-TWG-blueviolet)](https://thewidlarzgroup.com?utm_source=rnv&utm_medium=readme&utm_id=badge)




## 🔍 Features

- 📱 Plays all video formats natively supported by iOS/Android 
- ▶️ Local **and** remote playback  
- 🔁 Streaming: HLS • DASH • SmoothStreaming  
- 🔐 DRM: Widevine & FairPlay ([See free DRM stream example](https://www.thewidlarzgroup.com/services/free-drm-token-generator-for-video?utm_source=rnv&utm_medium=readme&utm_id=free-drm))
- 📴 **Offline playback**, video download, side-tracks, side-captions support (via [optional SDK](https://docs.thewidlarzgroup.com/offline-sdk?utm_source=rnv&utm_medium=readme&utm_id=features-text))  
- 🎚️ Fine-grained control over tracks, buffering & events
- 🧩 **Expo plugin** support
- 🌐 Basic Web Support 
- 📱 Picture in Picture
- 📺 TV Support



## ✨ Project status

| Version | State | Notes |
|---------|-------|-------|
| **v5 and lower** | ❌ *EOL* | No new development. [Commercial *maintenance & support* available](https://www.thewidlarzgroup.com/blog/react-native-video-upgrade-challenges-custom-maintenance-support?utm_source=rnv&utm_medium=readme&utm_id=upgrade-blog&utm_campaign=v5) |
| **v6** | 🛠 *Maintenance by community and [TWG](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=table)* | Accepting PRs. Fixing bugs.
| **v7** | 🚀 *In active development by [TWG](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=table)* | Public release *soon™*. Supports the new React Native architecture. [Become a **sponsor** for early access.](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_campaign=v7earlyaccess&utm_id=table#Contact) |

> **react-native-video** is a **community-based project** maintained by [TWG](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=comment-text) and an awesome open-source community.  
> Your sponsorship accelerates fixes, features, and the next major release. ❤️



## 🚀 Quick start

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






## 🧩 Optional modules

<a href="https://docs.thewidlarzgroup.com/offline-sdk?utm_source=rnv&utm_medium=readme&utm_id=banner" target="_blank">
  <img src="https://raw.githubusercontent.com/WiktorNiedzialkowski/react-native-video/master/docs/assets/baners/sdk-banner-retina-portrait.png" alt="Offline SDK Preview" width="35%" align="right" />
</a>

### 1 · 📥 Offline SDK

Enable offline streaming with full control over downloads, license lifecycle, secure storage and media access.

- Track selection (bitrate, audio, subtitles)  
- Pause / resume & background queueing  
- Expiration windows & auto-cleanup  
- Built for **Android & iOS**  
- → [SDK documentation](https://docs.thewidlarzgroup.com/offline-sdk?utm_source=rnv&utm_medium=readme&utm_id=modules-sdk-text)

---

### 2 · 🧪 Plugin architecture

Write your own plugins to extend download logic, attach analytics or add custom workflows – **without forking** the core SDK.  
[Read more](https://docs.thewidlarzgroup.com/react-native-video/other/plugin)



## 💼 TWG services & products

| Offering | Description |
|----------|-------------|
| [**Professional Support Packages**](https://www.thewidlarzgroup.com/services/free-drm-token-generator-for-video?utm_source=rnv&utm_medium=readme&utm_id=free-drm) | Priority bug-fixes, guaranteed SLAs, roadmap influence |
| [**Issue Booster**](https://www.thewidlarzgroup.com/issue-boost?utm_source=rnv&utm_medium=readme) | Pay‑per‑issue fast‑track for urgent fixes |
| [**Offline Video SDK**](https://www.thewidlarzgroup.com/offline-video-sdk/?utm_source=rnv&utm_medium=readme&utm_campaign=downloading&utm_id=offline-video-sdk-link) | Plug‑and‑play secure download solution for iOS & Android |
| [**Integration Support**](https://www.thewidlarzgroup.com/contact?utm_source=rnv&utm_medium=readme&utm_id=free-drm) | Hands‑on help integrating video, DRM & offline into your app |
| [**Free DRM Token Generator**](https://www.thewidlarzgroup.com/services/free-drm-token-generator-for-video?utm_source=rnv&utm_medium=readme&utm_id=free-drm) | Generate Widevine / FairPlay tokens for testing |
| [**Ready Boilerplates**](https://www.thewidlarzgroup.com/showcases?utm_source=rnv&utm_medium=readme) | Ready apps with background uploads, Offline HLS/DASH DRM, Video Frames Scrubbing, TikTok video roll, Frame Processor with Skia |
| [**React Native Video Upgrade Guide**](https://www.thewidlarzgroup.com/blog/react-native-video-upgrade-challenges-custom-maintenance-support?utm_source=rnv&utm_medium=readme&utm_id=upgrade-blog&utm_campaign=v7) | Common upgrade pitfalls & how to solve them |

*See how [TWG](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=services-text) helped **Learnn** ship a world‑class player in record time - [case study](https://gitnation.com/contents/a-4-year-retrospective-lessons-learned-from-building-a-video-player-from-scratch-with-react-native).*

## 📚 Documentation & Examples
- 📖 [Extensive documentation](https://docs.thewidlarzgroup.com/react-native-video/)
- 📦 **Guided examples**, DRM example with
[free DRM stream](https://www.thewidlarzgroup.com/services/free-drm-token-generator-for-video?utm_source=rnv&utm_medium=readme&utm_id=free-drm)


## 📰 Community & media

- 🗽 **React Summit US** - Learnn CTO explains how [TWG](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=community-media-text) Professional Services team fixed critical bugs and boosted video-player performance for their ed-tech platform. [Watch here »](https://gitnation.com/contents/a-4-year-retrospective-lessons-learned-from-building-a-video-player-from-scratch-with-react-native)  
- 🧨 **Nitro Module v7 deep‑dive** - Krzysztof from [TWG](https://www.thewidlarzgroup.com/?utm_source=rnv&utm_medium=readme&utm_id=community-media-text) is explaining why v7 is being written in Nitro Modules [Watch here »](https://x.com/krzysztof_moch/status/1854162551946478051)  


## 🌍 Social

- 🐦 **X / Twitter** - [follow product & release updates](https://x.com/TheWidlarzGroup)
- 💬 **Discord** - [talk to the community and us](https://discord.gg/9WPq6Yx)
- 💼 **LinkedIn** - [see TWG flexing](https://linkedin.com/company/the-widlarz-group)
