# japan_terebi-Desktop
 The macOS version of Japan Terebi

## Only works on macOS

### Instructions
- Download the zip file or clone this repository
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
