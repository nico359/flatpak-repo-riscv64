# Flatpak repo riscv64
To be honest I don't really know what to do with this yet, I'm kinda just doing this for fun and because I need to justify the purchase of both the MuseBook and now also the Milk-V Jupiter 2.

I'll add my own vibe coded apps for now as an experiment and maybe some others in the furure as well depending on how capable the Jupiter 2 will be.  
If I do end up adding a few apps not from me, I will of course take them down if anyone doesn't want me distributing their app through this unofficial repo.

## Adding the repo
You can add the repo hosted on a Cloudflare Bucket with the following command:  
```
flatpak remote-add flatpak-repo-riscv64 https://flatpak.ambatunat.buzz/repo/nico359-riscv64.flatpakrepo
```
Alternatively you can just download the .flatpakrepo file and add it with the graphical app of your choice (e.g. Gnome Software, KDE Discover, etc.):  
https://flatpak.ambatunat.buzz/repo/nico359-riscv64.flatpakrepo  

Then you should be able to find the apps like you would normally when using Flatpak.  
Also the needed runtimes are included in the repo.
