<p align="center"><br><img src="https://user-images.githubusercontent.com/236501/85893648-1c92e880-b7a8-11ea-926d-95355b8175c7.png" width="128" height="128" /></p>
<h3 align="center">Video Player</h3>
<p align="center"><strong><code>capacitor-video-player</code></strong></p>
<br>
<p align="center" style="font-size:50px;color:red"><strong>CAPACITOR 5 </strong></p><br>
<br>
<p align="center" style="font-size:50px;color:red"><strong>The ownership of this plugin is transfer to https://github.com/harmonwood who will ensure the maintenance </strong></p>

<!-- Note from the Owner - Start -->
<p align="center" style="font-size:50px;color:red"><strong>Note from the Owner</strong></p>
<!-- Note from the Owner - End -->
<br>
<!-- Message below Note from the Owner - Start -->
<p align="left" style="font-size:47px">Start --></p>
<br>
<p align="left">
I have been dedicated to developing and maintaining this plugin for many years since the inception of Ionic Capacitor. Now, at 73+ years old, and with my MacBook Pro becoming obsolete for running Capacitor 6 for iOS, I have made the decision to cease maintenance of the plugin. If anyone wishes to take ownership of this plugin, they are welcome to do so.  
</p>
<br>
<p align="left">
It has been a great honor to be part of this development journey alongside the developer community. I am grateful to see many of you following me on this path and incorporating the plugin into your applications. Your comments and suggestions have motivated me to continuously improve it.  
</p>
<br>
<p align="left">
I have made this decision due to several family-related troubles that require my full attention and time. Therefore, I will not be stepping back. Thank you to all of you for your support.
</p>
<br>
<p align="left" style="font-size:47px">End <--</p>
<!-- Message below Note from the Owner - End -->
<br>
<br>
<p align="center">
  Capacitor Video Player Plugin is a custom Native Capacitor plugin to play a video 
<br>
  <strong>fullscreen</strong> on IOS, Android, Web and Electron platforms
<br>
  <strong>embedded</strong> on Web and Electron platforms
</p>

<p align="center">
  <img src="https://img.shields.io/maintenance/yes/2023?style=flat-square" />
  <a href="https://github.com/jepiqueau/capacitor-video-player/actions?query=workflow%3A%22CI%22"><img src="https://img.shields.io/github/workflow/status/jepiqueau/capacitor-video-player/CI?style=flat-square" /></a>
  <a href="https://www.npmjs.com/package/capacitor-video-player"><img src="https://img.shields.io/npm/l/capacitor-video-player.svg?style=flat-square" /></a>
<br>
  <a href="https://www.npmjs.com/package/capacitor-video-player"><img src="https://img.shields.io/npm/dw/capacitor-video-player?style=flat-square" /></a>
  <a href="https://www.npmjs.com/package/capacitor-video-player"><img src="https://img.shields.io/npm/v/capacitor-video-player?style=flat-square" /></a>
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<a href="#contributors-"><img src="https://img.shields.io/badge/all%20contributors-8-orange?style=flat-square" /></a>
<!-- ALL-CONTRIBUTORS-BADGE:END -->
</p>

## Maintainers

| Maintainer        | GitHub                                    | Social |
| ----------------- | ----------------------------------------- | ------ |
| Quéau Jean Pierre | [jepiqueau](https://github.com/jepiqueau) |        |

## LATEST FOR CAPACITOR 5 (Master)

## Browser Support

The plugin follows the guidelines from the `Capacitor Team`,

- [Capacitor Browser Support](https://capacitorjs.com/docs/v3/web#browser-support)

meaning that it will not work in IE11 without additional JavaScript transformations, e.g. with [Babel](https://babeljs.io/).

## Installation

  ```bash
  npm install --save capacitor-video-player
  npx cap sync
  npx cap sync @capacitor-community/electron
  ```

### Build
  Then build YOUR_APPLICATION

  ```
  npm run build
  npx cap copy
  npx cap copy web
  npx cap copy @capacitor-community/electron
  npx cap open android
  npx cap open ios
  npx cap open @capacitor-community/electron
  npx cap serve
  ```

## Configuration

No configuration required for this plugin

## Supported methods

| Name                               | Android | iOS | Electron | Web |
| :--------------------------------- | :------ | :-- | :------- | :-- |
| initPlayer (mode fullscreen)       | ✅      | ✅  | ✅       | ✅  |
| initPlayer (mode embedded)         | ❌      | ❌  | ✅       | ✅  |
| initPlayer (url assets)            | ✅      | ✅  | ✅       | ✅  |
| initPlayer (url internal)          | ✅      | ✅  | ❌       | ❌  |
| initPlayer (url application/files) | ✅      | ✅  | ❌       | ❌  |
| initPlayer (subtitles)             | ✅      | ✅  | ❌       | ❌  |
| initPlayer (headers)               | ✅      | ✅  | ❌       | ❌  |
| initPlayer (title)                 | ✅      | ✅  | ❌       | ❌  |
| initPlayer (smallTitle)            | ✅      | ✅  | ❌       | ❌  |
| initPlayer (accentColor)           | ✅      | ❌  | ❌       | ❌  |
| initPlayer (chromecast)            | ✅      | ❌  | ❌       | ❌  |
| initPlayer (artwork)               | ✅      | ✅  | ❌       | ❌  |
| isPlaying                          | ✅      | ✅  | ✅       | ✅  |
| play                               | ✅      | ✅  | ✅       | ✅  |
| pause                              | ✅      | ✅  | ✅       | ✅  |
| getCurrentTime                     | ✅      | ✅  | ✅       | ✅  |
| setCurrentTime                     | ✅      | ✅  | ✅       | ✅  |
| getDuration                        | ✅      | ✅  | ✅       | ✅  |
| getMuted                           | ✅      | ✅  | ✅       | ✅  |
| setMuted                           | ✅      | ✅  | ✅       | ✅  |
| getVolume                          | ✅      | ✅  | ✅       | ✅  |
| setVolume                          | ✅      | ✅  | ✅       | ✅  |
| stopAllPlayers                     | ✅      | ✅  | ✅       | ✅  |
| getRate                            | ✅      | ✅  | ✅       | ✅  |
| setRate                            | ✅      | ✅  | ✅       | ✅  |
| showController                     | ✅      | ❌  | ❌       | ❌  |
| isControllerIsFullyVisible         | ✅      | ❌  | ❌       | ❌  |
| exitPlayer                         | ✅      | ❌  | ❌       | ❌  |

## Supported listeners

| Name                    | Android | iOS | Electron | Web |
| :---------------------- | :------ | :-- | :------- | :-- |
| jeepCapVideoPlayerReady | ✅      | ✅  | ✅       | ✅  |
| jeepCapVideoPlayerPlay  | ✅      | ✅  | ✅       | ✅  |
| jeepCapVideoPlayerPause | ✅      | ✅  | ✅       | ✅  |
| jeepCapVideoPlayerEnded | ✅      | ✅  | ✅       | ✅  |
| jeepCapVideoPlayerExit  | ✅      | ✅  | ✅       | ✅  |

## Documentation

[API_Documentation](https://github.com/jepiqueau/capacitor-video-player/blob/master/docs/API.md)

## Tutorials Blog

 - [JeepQ Capacitor Plugin Tutorials](https://jepiqueau.github.io/)



## Applications demonstrating the use of the plugin

### Capacitor 5 Apps

 - [ionic7-angular-videoplayer-app](https://github.com/jepiqueau/blog-tutorials-apps/tree/main/Videoplayer/ionic7-angular-videoplayer-app)

 - [vant-nuxt-videoplayer-app](https://github.com/jepiqueau/blog-tutorials-apps/tree/main/Videoplayer/vant-nuxt-videoplayer-app)


### Application Starter (Not yet updated to 5.0.0)

- [angular-video-player-app-starter](https://github.com/jepiqueau/angular-videoplayer-app-starter)

- [react-video-player-app-starter](https://github.com/jepiqueau/react-video-player-app-starter)

- [vite-react-videoplayer-app](https://github.com/jepiqueau/vite-react-videoplayer-app)
 
- [vue-videoplayer-app](https://github.com/jepiqueau/vue-videoplayer-app-starter)

## Usage 2.4.7

- [see capacitor documentation](https://capacitor.ionicframework.com/docs/getting-started/with-ionic)

- [see usage 2.4.7](https://github.com/jepiqueau/capacitor-video-player/blob/master/docs/Usage_2.4.7.md)

## Usage > 3.0.0 

- [see capacitor documentation](https://capacitor.ionicframework.com/docs/getting-started/with-ionic)

- [see usage > 3.0.0](https://github.com/jepiqueau/capacitor-video-player/blob/master/docs/Usage_3.0.0.md)

## Dependencies

- hls.js for HLS videos on Web and Electron platforms
- ExoPlayer for HLS, DASH, SmoothStreaming videos on Android platform

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/jepiqueau"><img src="https://avatars3.githubusercontent.com/u/16580653?v=4" width="100px;" alt=""/><br /><sub><b>Jean Pierre Quéau</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=jepiqueau" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/yelhouti"><img src="https://avatars.githubusercontent.com/u/5471639?v=4" width="100px;" alt=""/><br /><sub><b>Yelhouti</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=yelhouti" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/mamane10"><img src="https://avatars.githubusercontent.com/u/46500089?v=4" width="100px;" alt=""/><br /><sub><b>Mamane10</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=mamane10" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/KANekT"><img src="https://avatars.githubusercontent.com/u/580273?v=4" width="100px;" alt=""/><br /><sub><b>Пронин Андрей KANekT</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=KANekT" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/mueslirieger"><img src="https://avatars.githubusercontent.com/u/20973893?v=4" width="100px;" alt=""/><br /><sub><b>Michael Rieger</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=mueslirieger" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/PhantomPainX"><img src="https://avatars.githubusercontent.com/u/47803967?v=4" width="100px;" alt=""/><br /><sub><b>Manuel García Marín</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=PhantomPainX" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/j-oppenhuis"><img src="https://avatars.githubusercontent.com/u/46529655?v=4" width="100px;" alt=""/><br /><sub><b>Jelle Oppenhuis</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=j-oppenhuis" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/fegauthier"><img src="https://avatars.githubusercontent.com/u/12112673?v=4" width="100px;" alt=""/><br /><sub><b>fegauthier</b></sub></a><br /><a href="https://github.com/jepiqueau/capacitor-video-player/commits?author=fegauthier" title="Code">💻</a></td>
    
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
