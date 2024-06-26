# SpiffWorkflow landing page and blog

To get started, install Hugo. From there you can just run ```hugo serve``` and you should get the site as designed.

# Theme
We used the Fresh Theme
[![Documentation](https://img.shields.io/badge/Documentation-red)](https://stefma.github.io/hugo-fresh) 
[![Live Demo](https://img.shields.io/badge/Live%20Demo-blue)](https://hugo-fresh.vercel.app)

# Deployment
This is auto-deployed through CloudFlare's pages.  Please be sure that the correct version of Hugo is set in Cloud Flare's Workers & Pages / Settings / Environment Variables.

# Generating Animated gifs 
I used roughly a quarter of my standard screen to record videos with OBS Studio.
I then converted the mp4 files to gifs with the following command:
```bash
ffmpeg -i scripts.mp4 -r 15   -vf "scale=1024:-1,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" scripts.gif 

adding the following will speed the video up so it is 25% as long as it was originally.
-vf "setpts=0.25*PTS;"
```
