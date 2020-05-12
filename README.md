# japan_terebi-Desktop
 The macOS version of Japan Terebi

## Only works on macOS

### Instructions
For the normal installation:
- Download Japan Terebi for macOS at this address: [Japan Terebi for macOS [v2].dmg](https://japanterebi.netlify.app/assets/application/desktop/macOS/download/Japan_Terebi_for_macOS_[v2].dmg)
- Open the `.dmg` file
- Put the installation file inside of the `Applications` folder.
- Open the installation file inside of the `Applications` folder.
A `README.md` file is available in the `.dmg` file if you encounter any problem.

For the raw scripts:
- Download the zip file or clone this repository (and unzip if needed)
- Open the Installation file ` "Japan Terebi - Installation File" `
- During the installation, you will be prompted to press the enter key twice
- You can then open any of the TV Channels available

### Common Errors
- `No plugin can handle URL`
It means that the URL found isn't compatible with streamlink (the program used to get the raw stream)
#### What can I do?
Go to [the source checking webpage](https://dev-japanterebi.netlify.com/devtools/sources-check) (used by me to update all the links on Japan Terebi) or contact me.

- `No playable streams found on this URL`
It means that the URL is no longer a livestream and needs to be updated
#### What can I do?
Go to [the source checking webpage](https://dev-japanterebi.netlify.com/devtools/sources-check) or contact me.

### Change Profile
The `change profile` file is a file used to change the filter profile (upscale method/algorithm) applied to the stream to upscale it correctly.
4 profiles are available:
- `anime` (with the Anime4k algorithm)
- `anime-ultra` (with more filters from the Anime4k algorithm)
- `movie` (for real life footage, casual tv shows - with the SSimSuperRes algorithm)
- `movie-other` (same but with the FSRCNNX algorithm)


### Player Commands
- `g` --> Enabling the smoothner (motion interpolation)
- `G` (shift-g) --> Enabling all the smoothning and video enhancement filters (powerful CPU needed)
- `f` --> Toggle fullscreen
- `up` --> Volume up
- `down`-> Volume down
- `+` --> Add audio-delay (100ms)
- `-` --> Add audio-delay (-100ms)
- `a` --> Toggle mute
- `s` --> Toggle subtitles (if available)
- `i` --> Toggling interpolation
- `F4` --> Change aspect ratio
