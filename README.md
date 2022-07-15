# CoolSource
![coolsource_logo_improved](https://user-images.githubusercontent.com/44537796/138629825-eeca5164-3277-455a-8711-e27ebe3e5647.png)

# Features
1. BSP 21-22 support.
2. PBR support.
3. Restored Change Game in instance from HL1.
4. Compatible with most Source 2013 MP mods.
5. Can load CS:GO maps and most BSP 21 maps.
6. DX11 support.
7. DXVK support (need to copy hl2's dxvk-d3d9.dll in order to work).

# Current state
Buggy, incomplete and should not be use in production

# Compiling
## Windows
Requires [Visual Studio 2019 Community](https://visualstudio.microsoft.com/downloads/).  
When installing, go to the individual components and install such:
1. `C++ MFC for latest v142 build tools (x86 & x64)`
2. Optionally `C++ MFC for latest v142 build tools (x86 & x64)`
3. Latest Windows SDK, which should be installed by default

Enter the cool-source directory, after you've cloned it, and run the script `createallprojects.bat`. This should generate the `everything` solution. Open it with Visual Studio, select at the top to be Release (or optionally select Debug) and build it.  

## Linux
To be added