# UnityTemplate
Unity GitHub Repo Template

*Remember to copy and paste `.gitattributes` & `.gitignore` into it project sub folder.    
**Remember to protect it new repository branchs

# Branches Strategy
1. Develop: used to `programming` updates
2. Art: used to `art experiments like scenes concepts` and others `arts` stuff
3. Each new task should be a fork of it branch type like `develop_mobile_35` or `art_character_34`
4. The workflow should be: `task branch` like `develop_mobile_35` merged into `develop`, once ok the develop should be merged into `main` and `art` and `develop` should be updated from that new stable `main` branch

# Errors HotFix

## IF Unity incompatible version
1. IF on MacOS:
   1. install LFS command globally: `brew install git-lfs`
   2. install git lfs to repo: `git lfs install`
   3. pull LFS files: `git lfs pull`
1. If plastic error:
   1. Run: `plastic --configure` (or open plasitc)
   1. Sign In


# Rider <> Unity tips
1. Video for more information: https://www.youtube.com/watch?v=O1oOAM-AdbE
2. If Rider did not tagged the project as Unity Project, so it is necessary to open the root project folder on Rider, so Rider will set it up correctly

# Git Large Files

1. Duplicate the .gitignore from root dir to inside the Game Project dir
2. Install: 
   1. download and run the installer
   2. `git lfs install`
3. Add large files extension: 
   1. `git lfs track "*.psd" "*.png" "*.jpg" "*.jpg" "*.gif" "*.mp4" "*.mp3" "*.fbx"`
   2. `git lfs track "**.psd" "**.png" "**.jpg" "**.jpg" "**.gif" "**.mp4" "**.mp3" "**.fbx" "**.dll"`
4. Attributes tracker: `git add .gitattributes`
5. If git not tracking any extension run it: `git lfs migrate import --include="*.extension"`

# Unity Tips
1. Switch graphic manipulation: **QWERTY**
1. Lock Tab: lock Inspector tab to be able to select many Hierarchy elements without switching it Inspector visualization
