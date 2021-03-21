## Zee5 Player

### Features:
- Directly render HLS Player
- Free
- Can stream Premium Contents
- Serverless
- Can be deployed using Cloudflare Worker for free

### Usage:
*You can render Player in two methods 👇*

1. If <br><code>https://www.zee5.com/zee5originals/details/lalbazaar/0-6-2177/ep-1-sleepless-in-kolkata/0-1-manual_6a651ie4f1f0</code><br>
👆 this is the link <code>0-1-manual_6a651ie4f1f0</code> is the video id.<br>
**You can render a player like this <code>https://yourapp.example.workers.dev/0-1-manual_6a651ie4f1f0</code>**

2. Or you can render a Player using url parameter 👇<br>
<code>https://yourapp.example.workers.dev/?url=https://www.zee5.com/zee5originals/details/lalbazaar/0-6-2177/ep-1-sleepless-in-kolkata/0-1-manual_6a651ie4f1f0</code>

### Deploy:
*Deploy is Straight Forward. Follow these steps 👇*
- Star this repo 😉
- Copy the code of <code>[worker.js](https://github.com/cachecleanerjeet/Zee5/blob/main/worker.js "worker.js")</code>
- Create a [Cloudflare Worker](https://workers.cloudflare.com "Cloudflare Worker")
- Paste the copied code
- Save & Deploy

### I will not suggest to do this cheat. This repository is created to report the bug to Zee5.


<br><br>
<p align="center">
   
..
  <a href="https://www.instagram.com/prathameshpawar1189/">
    <img alt="Instagram" width="30px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.2.0/icons/instagram.svg" />
  </a>
..
 
..
  <a href="https://t.me/movietrigger">
    <img alt="Telegram" width="30px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.2.0/icons/telegram.svg" />
  </a>
  
</p>
