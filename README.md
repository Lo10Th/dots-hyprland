<div align="center">
    <h1>【 end_4's Hyprland dotfiles 】</h1>
    <h3></h3>
</div>

<div align="center">

![](https://img.shields.io/github/last-commit/end-4/dots-hyprland?&style=for-the-badge&color=FFB1C8&logoColor=D9E0EE&labelColor=292324)
![](https://img.shields.io/github/stars/end-4/dots-hyprland?style=for-the-badge&logo=andela&color=FFB686&logoColor=D9E0EE&labelColor=292324)
[![](https://img.shields.io/github/repo-size/end-4/dots-hyprland?color=CAC992&label=SIZE&logo=googledrive&style=for-the-badge&logoColor=D9E0EE&labelColor=292324)](https://github.com/end-4/hyprland)
![](https://img.shields.io/badge/issues-skill-green?style=for-the-badge&color=CCE8E9&logoColor=D9E0EE&labelColor=292324)
</a>

</div>

# ✨ Cool stuff
 <details open> 
  <summary>Notable features</summary>
     
  - Overview widget that shows open apps. Conveniently packed with app search/calculator/command runner
  - Autogenerated colors based on your wallpaper using [Material colors](https://m3.material.io/styles/color/the-color-system/key-colors-tones)
  - Fully animated widgets
</details>
 <details> 
  <summary>Bragging</summary>
     
   - [`summer-gruv`](https://github.com/end-4/dots-hyprland/tree/summer-gruv) branch: winner of Hyprland ricing competition Summer 2023, now shown in the [Hyprland repo](https://github.com/hyprwm/hyprland#gallery) and [Hyprland Wiki](https://wiki.hyprland.org/Configuring/Example-configurations/)
   - [`windoes`](https://github.com/end-4/dots-hyprland/tree/windoes) is a "Tasty rice" [on r/unixporn](https://www.reddit.com/r/unixporn/comments/13zdhqd/hyprland_windows_rice_with_too_much_eww_with_blur/)
</details>

# 👀 Styles

_Click the images for video showcases with animations! (except illogical\_impulse)_

### [illogical_impulse](https://github.com/end-4/dots-hyprland/tree/illogical-impulse)
   <a href="https://github.com/end-4/dots-hyprland/tree/illogical-impulse">
    <img src="./assets/illogical_impulse.png" alt="Sidebar, volume indicator and some GTK apps">
   </a>

### [m3ww](https://github.com/end-4/dots-hyprland/tree/m3ww)
   <a href="https://streamable.com/85ch8x">
    <img src="./assets/m3ww_sideright2.png" alt="Material Eww!">
   </a>

### [NovelKnock](https://github.com/end-4/dots-hyprland/tree/novelknock)
   <a href="https://streamable.com/7vo61k">
    <img src="./assets/novelknock-yellow.png" alt="Desktop Preview">
   </a>

### [Hybrid](https://github.com/end-4/dots-hyprland/tree/hybrid)
   <a href="https://streamable.com/4oogot">
    <img src="./assets/screenshot-hybrid.png" alt="click the circles!">
   </a>

### [Windoes](https://github.com/end-4/dots-hyprland/tree/windoes)
   <a href="https://streamable.com/5qx614">
    <img src="./assets/windoes-3.png" alt="Desktop Preview">
   </a>

- For older and insignificant styles, check the releases

---

# 🔧 General instructions
 - Don't download the main branch! Use one of the above listed ones.
 - **BACKUP**
 - Install dependencies. You can find the list for them in branch-specific readmes.
 - Copy
   - `.config`, `.local` to home folder
   - Folders in `.local/share/icons` to your `/usr/share/icons`
   - Stuff in `Import manually` folder if you need them
 - **For ARM users**: Compile .cpp files in `.config/eww/scripts/` (to that folder) (like this: `g++ ~/.config/ewwscripts/SCRIPTNAME.cpp -o ~/.config/eww/scripts/SCRIPTNAME`)
 
# 🎨 eww (yes I've spent too much time on this)
 ## Performance
|  ⌄  | Do use | Not recommended | Notes                 |
| --- | ------ | ----------- | ------------------------- |
| Kernel |     | cachyos, xanmod | Don't abuse power savers. Also I'm not sure what the hell I'm saying - this is just from personal experience. |
| Login shell  | bash/zsh | fish | It's okay to use fish in a terminal - that's what I do |

 ## Setup
 - This eww config only works properly in `~/.config/eww`
 - Start eww with `eww daemon`
 - To open top bar: `eww open bar`
 - To open the Windows bar: `eww open winbar` (`windoes`/`hybrid` branch)
 - To open the bottom line: `eww open bottomline` (so that the music window opens if you click the bottom edge of the screen)
 - Open the overview (middle-click workspaces) and wait 10 seconds (for it to generate app search cache, or icons won't show properly)
 ## Usage
 - Music controls: Middle-click for Play/Pause, Right-click for Next track, scroll to change volume
 - To open the Overview, middle/right-click the workspace indicators or run `eww open overview`
 - In overview, type to search apps (see more below)
 ## Search
 - Type normally to search apps
 - Type something beginning with a number and it'll be calculated (`qalc` is used for backend)
 - `>save THEME`: Saves current colorscheme, with THEME as the name.
 - `>load THEME`: Loads a saved theme. Available themes will be shown as you type.
 - `>music`: Get colorscheme from current media thumbnail
 - `>wall`: Get colorscheme from wallpaper located in `~/.config/eww/images/wallpaper/wallpaper` (might take quite a while)
 - `>light`: Remember to use light mode for next color generations
 - `>dark`: Remember to use dark mode for next color generations
 - `>one`: Remember to use only one color for bar icons for next color generations
 - `>multi`: Remember to use many colors for bar icons for next color generations
 - `>r`: Reload (kills and relaunches eww with the default bar)

---

# 🙏 Attribution
 - Thank you fufexan (who also thanks a lot more people) for his guidance and a simple, clean [eww config](https://github.com/fufexan/dotfiles) (good start for learning eww on hyprland btw)
 - Thanks to the people at the Hyprland discord server for their inspiration
 - Bing AI for helping me code like 80% of the C++ functions (lmao)
 - Maybe more, but I might not remember them all.. Still, thanks.

# 🌟 stonks
- _A star really makes my day! Thanks!_

[![Stars](https://starchart.cc/end-4/dots-hyprland.svg)](https://starchart.cc/end-4/dots-hyprland)

# 💡 Some inspirations
 - osu!lazer, Windows 11, Material Design 3, AvdanOS (concept)

