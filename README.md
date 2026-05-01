the text color will change to your accent color automatically

Idk how to make a widget file but made this for archival purpose. however you can copy past the main.qml file to `~/.local/share/plasma/plasmoids/com.github.prayag2.modernclock/contents/ui` or copy the lines with `//NEW` tag. only the threee lines with this tag is changed from the original code. also this is hardcoded (i don't know how to add this as a toggle either) so if you want to use custom colors again you have to remove the new line and uncomment the old line in main.qml

<details>
  <summary>Original Readme</summary>
  
  <p align="center">
  <img src="https://github.com/Prayag2/kde_modernclock/blob/main/assets/logo.jpg" width=100/>
  <h2 align="center">Modern Clock for KDE</h2>
  <p align="center">A modern looking clock widget!</center>
</p>

<p align="center">
<a href="https://github.com/prayag2/kde_modernclock/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/prayag2/kde_modernclock?color=%233DAEE9&style=for-the-badge"></a>
<a href="https://github.com/prayag2/kde_modernclock/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/prayag2/kde_modernclock?color=%233DAEE9&style=for-the-badge"></a>
<a href="https://github.com/prayag2/kde_modernclock/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/prayag2/kde_modernclock?color=%233DAEE9&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="https://github.com/Prayag2/kde_modernclock/blob/main/assets/ss.png"/>
</p>

## Installation
#### KDE Store (Preferred way)
1. Right click on the desktop
2. Click on "Add Widgets"
3. Click on "Get New Widgets"
4. Click on "Download New Plasma Widgets"
5. Search for "Modern Clock"
6. Click on "Install" and you're done!

#### From this repository
1. Clone this repository  
`git clone https://github.com/prayag2/kde_modernclock && cd kde_modernclock/`  
2. Install using the script  
`kpackagetool5 -i package`

</details>
