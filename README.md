# Absinth's MPV config
My own mpv config, using vulkan api.

Made for watching anime but can be used for TV shows and movies.

## HOW TO INSTALL:

1) DROP MPV FOLDER TO YOUR %APPDATA% FOLDER

2) INSTALL FONT FROM FONT FOLDER 

3) CHANGE COMPUTER USERNAME IN SHADERS DIRECTORIES FROM MY (TROYA) TO YOUR'S

example:
 >glsl-shaders-append="C:\Users\Troya\AppData\Roaming\mpv\shaders/KrigBilateral.glsl"
 
to

 >glsl-shaders-append="C:\Users\YourUsername\AppData\Roaming\mpv\shaders/KrigBilateral.glsl"
 
 4) Start Your mpv and you should be able to see that it works, right click opens up menu.

## Used shaders:
- SSimDownscaler (Luma downscale)
- FSRCNNX_x2_8-0-4-1 (Luma upscale)
- KrigBilateral (Chroma downscale and upscale)
- static luma noise (because mpv grain deband sucks)
- static chroma noise (because mpv grain deband sucks)

## Used scripts:
- autoload.lua
- uosc.lua
