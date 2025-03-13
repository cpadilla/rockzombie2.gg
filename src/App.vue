<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <div class="top-container">
      <div class="container">
        <img class="portrait" src="./assets/rockzombie2.jpg" />
      </div>
      <div class="container">
        <p class="username">rockzombie2</p>
      </div>
      <div class="image-container">
          <div class="container">
            <div class="icon-row">
                <div class="icon">
                  <a href="https://youtube.com/rockzombie2" target="_blank">
                    <img src="./assets/youtube.svg" class="logo youtube" alt="YouTube logo" />
                  </a>
                </div>
                <div class="icon">
                  <a href="https://discord.com/users/188799069668245514" target="_blank">
                    <img src="./assets/discord.svg" class="logo discord" alt="Discord logo" />
                  </a>
                </div>
                <div class="icon">
                  <a href="https://twitch.tv/rockzombie2" target="_blank">
                    <img src="./assets/twitch.svg" class="logo twitch" alt="Twitch logo" />
                  </a>
                </div>
            </div>
          </div>
          <div class="container">
            <div class="icon-row">
                <div class="icon">
                  <a href="https://bsky.app/rockzombie2.gg" target="_blank">
                    <img src="./assets/bluesky.svg" class="logo bluesky" alt="Bluesky logo" />
                  </a>
                </div>
                <div class="icon">
                  <a href="https://christofer.rocks" target="_blank">
                    <img src="./assets/cube.gif" class="logo blog" alt="Blog logo" />
                  </a>
                </div>
                <div class="icon">
                  <a href="https://www.instagram.com/rockzombie2" target="_blank">
                    <img src="./assets/instagram.svg" class="logo instagram" alt="Instagram logo" />
                  </a>
                </div>
            </div>
          </div>
          <div class="container">
            <div class="icon-row">
                <div class="icon">
                  <a href="https://www.tiktok.com/@rockzombie2" target="_blank">
                    <img src="./assets/tiktok.svg" class="logo tiktok" alt="TikTok logo" />
                  </a>
                </div>
                <div class="icon">
                  <a href="https://reddit.com/u/rockzombie2" target="_blank">
                    <img src="./assets/reddit.svg" class="logo reddit" alt="Reddit logo" />
                  </a>
                </div>
                <div class="icon">
                  <a href="https://open.spotify.com/user/christoferpadilla" target="_blank">
                    <img src="./assets/spotify.svg" class="logo spotify" alt="Spotify logo" />
                  </a>
                </div>
            </div>
          </div>
      </div>
  </div>
</template>

<style scoped>
.portrait {
  max-width: 600px;
  width: 100%;
}
.top-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.image-container {
    max-width: 800px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.container {
  width: 100%;
}
.username {
  font-weight: bold;
  font-size: x-large;
  margin: 0;
}
.icon-row {
  width: 100%;
  display: table;
  border-collapse: separate;
}
img {
   pointer-effects: none
}
a {
    text-align: -webkit-center;
}
.icon {
  display: table-cell;
  text-align: center;
  vertical-align: middle;
}
/*###Desktops, big landscape tablets and laptops(Large, Extra large)####*/
@media screen and (min-width: 1024px){
/*Style*/
    .logo {
      display: table-cell;
      text-align: center;
      vertical-align: middle;
      border: none;
      width: 6em;
      padding: 1.5em;
      will-change: filter;
      transition: filter 300ms;
    }
}

/*###Tablet(medium)###*/
@media screen and (min-width : 768px) and (max-width : 1023px){
/*Style*/
    .logo {
      display: table-cell;
      text-align: center;
      vertical-align: middle;
      border: none;
      width: 6em;
      padding: 1.5em;
      will-change: filter;
      transition: filter 300ms;
    }
}

/*### Smartphones (portrait and landscape)(small)### */
@media screen and (min-width : 0px) and (max-width : 767px){
/*Style*/
    .logo {
      display: table-cell;
      text-align: center;
      vertical-align: middle;
      border: none;
      width: 3.7em;
      padding: 1em;
      will-change: filter;
      transition: filter 300ms;
    }
}
.logo.youtube:hover {
  filter: drop-shadow(0 0 2em #FF0000aa);
}
.logo.discord:hover {
  filter: drop-shadow(0 0 2em #5865F2aa);
}
.logo.twitch:hover {
  filter: drop-shadow(0 0 2em #9146FFaa);
}
.logo.bluesky:hover {
  filter: drop-shadow(0 0 2em #1185feaa);
}
.logo.instagram:hover {
  filter: drop-shadow(0 0 2em #dc7e9dfe);
}
.logo.tiktok:hover {
  filter: drop-shadow(0 0 2em #6bcad3aa);
}
.logo.spotify:hover {
  filter: drop-shadow(0 0 2em #1ED760aa);
}
.logo.reddit:hover {
  filter: drop-shadow(0 0 2em #FF5700aa);
}
.logo.blog:hover {
  filter: drop-shadow(0 0 2em #FFFFFFaa);
}
</style>
