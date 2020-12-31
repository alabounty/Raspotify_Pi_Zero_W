# Raspotify_Pi_Zero_W
My project using a Raspberry Pi Zero W as a Spotify player

## Components
1. Raspberry Pi Zero W
2. Raspiaudio Audio+ DAC - https://www.amazon.com/gp/product/B00MDW602K/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1
3. Any powered speakers
4. Power adapter for Pi Zero
5. (Optional) 3d printed case

## Software
1. Raspberry Pi OS (2020-12-02)
2. Raspotify - https://pimylifeup.com/raspberry-pi-spotify/
   a. sudo apt install -y apt-transport-https curl
   b. curl -sSL https://dtcooper.github.io/raspotify/key.asc | sudo apt-key add -v -
      echo 'deb https://dtcooper.github.io/raspotify raspotify main' | sudo tee /etc/apt/sources.list.d/raspotify.list
3. Raspiaudio - https://forum.raspiaudio.com/t/audio-installation-guide/19
   a. sudo wget -O - script.raspiaudio.com | bash
