# lug-wine

wine-4.18-145-g237d563627 (Staging)
WoW64 biarch Build from 28. October 2019

This is a Lutris runner for StarCitizen !

This runner offers no fsync() support !
When you run into a black screen, make sure you have vcrun2017/vcredist and d3dcompiler_47 installed in your prefix.
You may have to copy the d3dcompiler_47.dll from the launcher dir to the games /Bin64 folder.

Important:

People reporting issues with symlinks in the ZIP download ! You want to git clone the runner to keep the symlinks inside the runner. To do that, you enter the following in your bash, i have the git clone in ~/src:

cd ~/src

git clone https://github.com/rawfoxDE/lug-wine.git ./lug-wine

That will clone the runner into /home/you/src/lug-wine

To use it under Lutris, copy or symlink the directory '/home/you/src/lug-wine/lug-sc-wine' to your Lutris runners. 
You may find them under '/home/you/.local/share/lutris/runners/wine'.

After that, tweak your Lutris game configuration to set the runner as 'Custom'. 
In the line below you point to the new wine executable under '/home/you/.local/share/lutris/runners/wine/lug-sc-wine/bin/wine64'

For help and support, join the Linux Users Group at CIG. 

https://robertsspaceindustries.com/spectrum/community/LUG/lobby/104

Find the main installation thread here:

https://robertsspaceindustries.com/spectrum/community/LUG/forum/149/thread/star-citizen-on-linux-information-thread-readme
