# AniTeams player 
## how to setup 
#### Artplayer 
- go to the index.html file line 22 and 23 you will find this
```javascript
  const proxyUrl = 'https://gogoanime-and-hianime-proxy-ten.vercel.app/m3u8-proxy?url=';  // https://github.com/JulzOhern/Gogoanime-and-Hianime-proxy
const apiUrl = 'https://aniwatch-api-net.vercel.app/api/v2/hianime/episode/sources';  // https://github.com/ghoshRitesh12/aniwatch-api
```
update those valuse with your deployed version 

#### plyr
- go to the folder plyr and then the index.html file line 87
```javascript
const apiUrl = `https://aniwatch-api-net.vercel.app/api/v2/hianime/episode/sources?animeEpisodeId=${id}&server=${server}&category=${category}`;
```
and line 106
``` jabascript
 const proxyUrl = `https://gogoanime-and-hianime-proxy-ten.vercel.app/m3u8-proxy?url=${encodeURIComponent(hlsSource.url)}`; // https://github.com/JulzOhern/Gogoanime-and-Hianime-proxy
```
update those values with your deployed version 
