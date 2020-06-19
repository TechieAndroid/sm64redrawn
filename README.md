# sm64redrawn

![Screenshot](screenshot.png)



## This is a collection of textures that have been redrawn for the Super Mario 64 port.



### Contributors

**Myself, cazsu, CyberCat, garrit[jkl], Mazeo, Ray, roovahlees, Specialfred453, Teaufou, The Chain Smoker**

This is the result of many hours of manual work drawing these textures at 10x scale or higher.

Remember to give credit to this pack if you plan to use it in a video or other form of social media, you can also link to it here. Thank you :)

Do not redistribute this pack without explicit permission.

If you're interested and would like to help out, check out our Discord server! -> https://discord.gg/7bcNTPK



### Installation

If you need help compiling the source I've added the insructions below.

Extract the zip file and copy it's contents into the `res` directory inside your `build` directory.

If asked to write into subdirectories and overwrite files hit yes. This way you'll get all the textures that have been redrawn, while leaving the originals that haven't been redrawn yet intact.

### Source Compilation

This is a basic guide and if you need more information you should look at the readme here -> https://github.com/sm64pc/sm64pc/tree/nightly

`git clone -b nightly https://github.com/sm64pc/sm64pc.git`

`make NODRAWINGDISTANCE=1 TEXTURE_FIX=1 EXTERNAL_DATA=1`

Add the flag `BETTERCAMERA=1` when building if you want more freedom with your camera.
