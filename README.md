<!-- markdownlint-disable MD041-->
[//]: # (auto_md_to_doc_comments segment start A)

# photos_to_slideshow

[//]: # (auto_cargo_toml_to_md start)

**My personal worflow from photos to slideshow (2025-02)**  
***author: [bestia.dev](https://bestia.dev) repository: [GitHub](https://github.com/bestia-dev/photos_to_slideshow)***  

[//]: # (auto_cargo_toml_to_md end)

 ![work_in_progress](https://img.shields.io/badge/work_in_progress-yellow)
 [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/bestia-dev/photos_to_slideshow/blob/master/LICENSE)
 ![photos_to_slideshow](https://bestia.dev/webpage_hit_counter/get_svg_image/1647060273.svg)

Hashtags: #english #photos  
My projects on Github are more like a tutorial than a finished product: [bestia-dev tutorials](https://github.com/bestia-dev/tutorials_rust_wasm).

## Motivation

When I go on vacation I take thousands of photos from different devices.  
It is chaos.
I want to tame the chaos, but it is not easy.
The only thing that I really know about a photo is the moment it is taken.  
So I prefer to name the photos by date and time in this format `2025-12-31 23-59-59`.  
But I want to know which photos are mine and which photos are from my friends. So I append a prefix "LF" to make the difference.

# ffmpeg is great

## install in debian

sudo apt-get update
sudo apt-get install ffmpeg

## ffmpeg merge subtitles

ffmpeg -i "LF2025-01-26 Egypt.mkv" -vf subtitles="LF2025-01-26 Egypt.srt:force_style='FontSize=28'" "LF2025-01-26 Egypt.mp4"

## Cut mp3 file

ffmpeg -ss 462 -i "input.mp3" -acodec copy "output.mp3"


## Open-source and free as a beer

My open-source projects are free as a beer (MIT license).  
I just love programming.  
But I need also to drink. If you find my projects and tutorials helpful, please buy me a beer by donating to my [PayPal](https://paypal.me/LucianoBestia).  
You know the price of a beer in your local bar ;-)  
So I can drink a free beer for your health :-)  
[Na zdravje!](https://translate.google.com/?hl=en&sl=sl&tl=en&text=Na%20zdravje&op=translate) [Alla salute!](https://dictionary.cambridge.org/dictionary/italian-english/alla-salute) [Prost!](https://dictionary.cambridge.org/dictionary/german-english/prost) [Nazdravlje!](https://matadornetwork.com/nights/how-to-say-cheers-in-50-languages/) 🍻

[//bestia.dev](https://bestia.dev)  
[//github.com/bestia-dev](https://github.com/bestia-dev)  
[//bestiadev.substack.com](https://bestiadev.substack.com)  
[//youtube.com/@bestia-dev-tutorials](https://youtube.com/@bestia-dev-tutorials)  

[//]: # (auto_md_to_doc_comments segment end A)
