# Absinth's MPV config
My own mpv config, using vulkan api.

Made for watching anime but can be used for TV shows and movies.

## HOW TO INSTALL:

1) DROP MPV FOLDER TO YOUR %APPDATA% FOLDER

2) CHANGE COMPUTER USERNAME IN SCRIPT FROM MY (TROYA) TO YOUR'S

example:
 >glsl-shaders-append="C:\Users\Troya\AppData\Roaming\mpv\shaders/KrigBilateral.glsl"
 
to

 >glsl-shaders-append="C:\Users\YourUsername\AppData\Roaming\mpv\shaders/KrigBilateral.glsl"

## Used shaders:
- SSimDownscaler (Luma downscale)
- FSRCNNX_x2_8-0-4-1 (Luma upscale)
- KrigBilateral (Chroma downscale and upscale)
- static luma noise
- static chroma noise

## Used scripts:
- autoload.lua
