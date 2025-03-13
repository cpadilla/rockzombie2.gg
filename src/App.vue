<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <img class="portrait" src="./assets/rockzombie2.jpg" />
  </div>
  <div>
    <p class="username">rockzombie2</p>
  </div>
  <div>
    <div>
      <a href="https://youtube.com/rockzombie2" target="_blank">
        <img src="./assets/youtube.svg" class="logo youtube" alt="YouTube logo" />
      </a>
      <a href="https://twitch.tv/rockzombie2" target="_blank">
        <img src="./assets/twitch.svg" class="logo twitch" alt="Twitch logo" />
      </a>
    </div>
  </div>
  <div>
    <div>
      <a href="https://bsky.app/rockzombie2.gg" target="_blank">
        <img src="./assets/bluesky.svg" class="logo bluesky" alt="Bluesky logo" />
      </a>
      <a href="https://www.instagram.com/rockzombie2" target="_blank">
        <img src="./assets/instagram.svg" class="logo instagram" alt="Instagram logo" />
      </a>
    </div>
  </div>
  <div>
    <div>
      <a href="https://www.tiktok.com/@rockzombie2" target="_blank">
        <img src="./assets/tiktok.svg" class="logo tiktok" alt="TikTok logo" />
      </a>
      <a href="https://open.spotify.com/user/christoferpadilla" target="_blank">
        <img src="./assets/spotify.svg" class="logo spotify" alt="Spotify logo" />
      </a>
    </div>
  </div>
  <div>
    <div>
      <a href="https://christofer.rocks" target="_blank">
        <img src="./assets/cube.gif" class="logo blog" alt="Blog logo" />
      </a>
    </div>
  </div>
</template>

<style scoped>
.portrait {
  max-width: 600px;
}
.username {
  font-weight: bold;
  font-size: x-large;
}
img {
   pointer-effects: none
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo.youtube:hover {
  filter: drop-shadow(0 0 2em #FF0000aa);
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
.logo.blog:hover {
  filter: drop-shadow(0 0 2em #000000aa);
}
</style>
