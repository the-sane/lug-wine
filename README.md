# lug-wine

wine-4.15 (Staging) Build from 1. September 2019

This is a Lutris runner for StarCitizen !

Important:

People reporting issues with symlinks in the ZIP download ! You want to git clone the runner to keep the symlinks inside the runner. To do that, you enter the following in your bash, i have the git clone in ~/src:

cd ~/src

git clone https://github.com/rawfoxDE/lug-wine.git ./lug-wine

That will clone the runner into your ~/src/lug-wine

To use it under Lutris, copy or symlink the 'raw-wine/' directory in '/home/you/src/lug-wine' to your Lutris runners. You may find them under '~/.local/share/lutris/runners/wine'.

After that, tweak your Lutris game configuration to set the runner as 'Custom'. In the line below you point to the new wine executable under '~/.local/share/lutris/runners/wine/raw-wine/bin/wine64'

For help and support, join the Linux Users Group at CIG. 

https://robertsspaceindustries.com/spectrum/community/LUG/lobby/104

Find the main installation thread here:

https://robertsspaceindustries.com/spectrum/community/LUG/forum/149/thread/star-citizen-on-linux-information-thread-readme
