
# selfhosted-music-overview

selfhosted-music-overview intends to provide an overview of different self-hostable music streaming sites.




## Server Overview



|                                                                 | Open Source | Internal Access | Scrobble Plays | Can Read Tags    | Can Write Tags   | Subsonic API | Can Share Music | Multi-User Support | Multi-Library Support | Smart Playlists | Heart/Favorites | 5 Star Rating | Replay Gain | Demo                                                                                                          | Transcode |
| --------------------------------------------------------------- | ----------- | --------------- | ------------- | ---------------- | ---------------- | ------------ | --------------- | ----------------- | -------------------- | --------------- | --------------- | ------------- | ----------- | ------------------------------------------------------------------------------------------------------------- | --------- |
| [Plex](https://github.com/plexinc/)                             | No          | Yes, Paid       |               | Yes              | Yes              | No           | Yes, Paid       | Yes               | Yes                  | Yes             | Yes             |               |             | [Yes](https://app.plex.tv/desktop/#!/)                                                                        |           |
| [Emby](https://github.com/MediaBrowser/Emby)                    | Sorta       | Yes             |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [Jellyfin](https://jellyfin.org/)                               | Yes         | Yes             | Yes, Plugin   | Yes              | Yes              | No           | Yes             | Yes               | Yes                  | No              | Yes             | No            | No          | [Yes](https://demo.jellyfin.org/stable/web/index.html#!/login.html?serverid=713dc3fe952b438fa70ed35e4ef0525a) | Yes       |
| [Navidrome](https://github.com/navidrome)                       | Yes         |                 | Yes           | Yes              | No               | Yes          | Yes             | Yes               | No, Future           | No, Future      | Yes             | Yes           | Yes         | [Yes](https://www.navidrome.org/demo/)                                                                        | Yes       |
| [Airsonic](https://airsonic.github.io/)                         | Yes         |                 |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [Subsonic](https://github.com/subsonic)                         | No          |                 |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [Funkwhale](https://funkwhale.audio/)                           | Yes         |                 |               |                  |                  | Yes          | Yes             |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [LMS](https://github.com/epoupon/lms)                           |             |                 | Yes           | Yes, Multi-Value | Yes, Multi-Value | Yes          |                 | Yes               |                      | Yes             | Yes             |               |             | [Yes](https://lms.demo.poupon.io/)                                                                            |           |
| [mStream](https://mstream.io/)                                  | Yes         |                 |               |                  |                  |              | Yes             |                   |                      | No              |                 | Yes           | Yes         | [Yes](https://demo.mstream.io/?)                                                                              | Yes       |
| [Ampache](https://ampache.org/)                                 | Yes         | Yes             |               | Yes              | Yes, File or DB  | Yes          |                 | Yes               |                      | Yes             | Yes             | Yes           |             | Yes                                                                                                           | Yes       |
| [Mopidy](https://docs.mopidy.com/)                              |             |                 |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [Koel](https://koel.dev/)                                       |             |                 |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [MPD](https://www.musicpd.org/)                                 |             |                 |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [Serviio](https://www.serviio.org/)                             |             |                 |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |
| [Logitech Media Server](https://www.mysqueezebox.com/download)  |             |                 |               |                  |                  |              |                 |                   |                      |                 |                 |               |             |                                                                                                               |           |



## Client Overview



|             |                               | Current Version | Album View | Song List | Folder View | Artist View | Genre View | List by decade | List by year | Playlist Support | Most Played Song | Most Played Album | Recently Played Song | Recently Played Album | Recently Added Song | Recently Added Album | Offline Mode | Download Music | Podcasts | Last.FM Scrobbling | Similar Songs | Show Top songs of an artist | Shuffle Play | Favourites / Starred / Bookmark | 5 Stars | Search function | Chromecast Support | Android Auto | mp3 | opus | flac | Dark Mode | Themeable | License | Open Source | Price Tag | Smart Recommendations | Link                                                                                             |
| ----------- | ----------------------------- | --------------- | ---------- | --------- | ----------- | ----------- | ---------- | -------------- | ------------ | ---------------- | ---------------- | ----------------- | -------------------- | --------------------- | ------------------- | -------------------- | ------------ | -------------- | -------- | ------------------ | ------------- | --------------------------- | ------------ | ------------------------------- | ------- | --------------- | ------------------ | ------------ | --- | ---- | ---- | --------- | --------- | ------- | ----------- | --------- | --------------------- | ------------------------------------------------------------------------------------------------ |
| **Android** | Gelli                         |                 |            |           |             |             |            |                |              |                  |                  |                   |                      |                       |                     |                      |              |                |          |                    |               |                             |              |                                 |         |                 |                    |              |     |      |      |           |           |         |             |           |                       |                                                                                                  |
| **Android** | Finamp                        | 0.5.1           |            |           |             |             |            |                |              |                  |                  |                   |                      |                       |                     |                      |              |                |          |                    |               |                             |              |                                 |         |                 |                    |              |     |      |      |           |           |         |             |           |                       |                                                                                                  |
| **Android** | substreamer - Subsonic Client |                 | Yes        | Yes       | Yes         | Yes         |            | Yes            | No           | Yes              |                  |                   |                      |                       |                     |                      | Yes          | Yes            | Yes      | Yes                | Yes           | Yes                         | Yes          | Yes                             | No      | Yes             |                    |              | Yes | Yes  | ?    | Yes       | No        |         | No          | free      | Yes                   | [Substreamer](https://play.google.com/store/apps/details?id=com.ghenry22.substream2&hl=en&gl=US) |
| **Android** | Ultrasonic                    | 2.23.1          | Yes        | No        | No          | Yes         | No         | No             | Yes          | Yes              | No               | Yes               | No                   | Yes                   | No                  | Yes                  | No           | Yes            |          | Yes                |               |                             | Yes          | Yes                             | Yes     | Yes             | No                 | No           | Yes |      | Yes  | Yes       |           |         |             |           |                       |                                                                                                  |
| **Android** | Funkwhale for Android         |                 |            |           |             |             |            |                |              |                  |                  |                   |                      |                       |                     |                      |              |                |          |                    |               |                             |              |                                 |         |                 |                    |              |     |      |      |           |           |         |             |           |                       |                                                                                                  |
| **Android** | Subtracks                     |                 |            |           |             |             |            |                |              |                  |                  |                   |                      |                       |                     |                      |              |                |          |                    |               |                             |              |                                 |         |                 |                    |              |     |      |      |           |           |         |             |           |                       |                                                                                                  |
| **Android** | Dsub                          | 5.5.2           |            |           |             |             |            |                |              |                  |                  |                   |                      |                       |                     |                      |              |                |          |                    |               |                             |              |                                 |         |                 | Yes                |              |     |      |      |           |           |         |             |           |                       |                                                                                                  |
| **Android** | Audinaut                      |                 |            |           |             |             |            |                |              |                  |                  |                   |                      |                       |                     |                      |              |                |          |                    |               |                             |              |                                 |         |                 |                    |              |     |      |      |           |           |         |             |           |                       |                                                                                                  |
| **Android** | Subsonic                      |                 |            |           |             |             |            |                |              |                  |                  |                   |                      |                       |                     |                      |              |                |          |                    |               |                             |              |                                 |         |                 |                    |              |     |      |      |           |           |         |             |           |                       |                                                                                                  |
| **Web**     | Navidrome                     | Yes             | Yes        | Yes       | No          | Yes         | Yes        | No             | Yes          | Yes              | Yes              | Yes               | Yes                  | Yes                   | Yes                 | Yes                  | No           | Yes            | No       | Yes                | No            | No                          | Yes          | Yes                             | No      | Yes             |                    |              | Yes | Yes  | Yes  | Yes       | Yes       | GPL3    | Yes         | free      | No                    | [Navidrome](https://github.com/navidrome)                                                        |

## How to Contribute

tba
