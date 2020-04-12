# Absinth's MPV config
My own mpv config, using vulkan api.

HOW TO INSTALL:
-DROP MPV FOLDER TO YOUR %APPDATA% FOLDER
-CHANGE USERNAME OF YOUR COMPUTER FROM MY (TROYA) TO YOURS IN SCRIPTS DIRECTORY
example:
 >glsl-shaders-append="C:\Users\Troya\AppData\Roaming\mpv\shaders/KrigBilateral.glsl"
to
 >glsl-shaders-append="C:\Users\YourUsername\AppData\Roaming\mpv\shaders/KrigBilateral.glsl"

Used shaders:
- SSimDownscaler (Luma downscale)
- FSRCNNX_x2_8-0-4-1 (Luma upscale)
- KrigBilateral (Chroma downscale and upscale)
- static luma noise
- static chroma noise

Used scripts:
- autoload.lua
