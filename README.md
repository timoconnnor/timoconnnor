
//Banner
<p class="line-1 anim-typewriter">Hi, I'm Tim and this is my Github</p>
/* Google Fonts */
@import url('https://fonts.googleapis.com/css?family=Anonymous+Pro');

/* Global */
body {
  height: 100vh;
  margin: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Anonymous Pro', monospace;
  background-color: #2a2a2a; /* Dark gray background */
  color: #fff;
  overflow: hidden;
  background-image: url(https://wallpapercave.com/dwp2x/wp4180015.jpg); /* Add the image path here */
  background-repeat: repeat;
  background-size: auto;
  background-position: center 30%;
  background-size: 60%
}

.line-1 {
  position: relative;
  width: 24em;
  border-right: 2px solid rgba(255, 255, 255, 0.75);
  font-size: 2.5rem; /* Adjust font size */
  text-align: center;
  white-space: nowrap;
  overflow: hidden;
}

/* Animation */
.anim-typewriter {
  animation: typewriter 4s steps(44) 1s 1 normal both, blinkTextCursor 500ms steps(44) infinite normal;
}
@keyframes typewriter {
  from {
    width: 0;
  }
  to {
    width: 24em;
  }
}
@keyframes blinkTextCursor {
  from {
    border-right-color: rgba(255, 255, 255, 0.75);
  }
  to {
    border-right-color: transparent;
  }
}

/* Hover Animation */
.line-1:hover {
  animation: none;
  border-right: 2px solid #FFC107; /* Yellow border on hover */
  animation: borderBlink 0.8s infinite alternate;
}

@keyframes borderBlink {
  0% {
    border-right-color: rgba(255, 255, 255, 0.75);
  }
  100% {
    border-right-color: #FFC107;
  }
}



<h2> What's good, I'm Tim <img src="(https://giphy.com/gifs/thebossbaby-food-baby-3o6Yg725hMPzA5sxyg)" width="50"></h2>


<p1> I'm an absolute coding machine... beware </p1>

<p align="center">
  <a href="https://github.com/timoconnnor">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/white">
      <img alt="GitHub" title="GitHub" height="48" width="48" src="https://cdn.simpleicons.org/github"></picture></a>
  <a href="https://www.linkedin.com/public-profile/settings?trk=d_flagship3_profile_self_view_public_profile">
    <img alt="LinkedIn" title="LinkedIn" height="48" width="48" src="https://cdn.simpleicons.org/linkedin"></a>
  <a href="https://www.instagram.com/timoconnorrrr/">
    <img alt="ig" title="ig" height="48" width="48" src="https://simpleicons.org/icons/instagram.svg"></a>
</p>

---
[![Tim's's GitHub stats](https://github-readme-stats.vercel.app/api?username=timoconnnor)](https://github.com/timoconnnor/github-readme-stats)
