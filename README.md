# Minecraft-Modding-Test
A repository For Minecraft Mods. Testing out how to mod minecraft with eclipse (IDE). gradlew setupDecompWorkspace and gradlew eclipse were used to set up the workspace to actually start modding (To set up the workspace).

# Instalation
STEP 1: Instal eclipse, a minecraft forge version (version 1.12.2 or above), has to be a Forge MDK (Modders Development Kit) file aswell.

STEP 2:Create a new folder (call this folder 1) and within the folder create another folder (folder 2) for the contents of your mod (eg. your src, main, etc will be here).

STEP 3: Move eclipse into folder 1 and all of the forge files into folder 2. 

STEP 4:open up your command line (type cmd into the windows search bar) and go into folder 2's directory (will be something like CD "C:\Users\User\Desktop\Folder 1\Folder 2" and type "gradlew setupDecompWorkspace".

STEP 5: When that successfully builds and sets up the environment for modding, type "gradlew eclipse" to add and download some extra files for eclipse to use when compiling. Now wait until this builds.

STEP 6: Now you have most of your files and the environment for modding ready. open up folder 2 and notice the folder "src" in there. open the "src" folder and you will find the "main" folder inside. download MY "main" folder from github and replace the "main" folder within "folder 2" from YOUR computer. 

STEP 7: Run eclipse and when it asks you to choose a directory for a workspace, choose the eclipse folder within forlder 2 (eg "C:\Users\user\Desktop\Folder 1\Folder 2\eclipse"

