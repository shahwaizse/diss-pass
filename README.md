https://wiki.archlinux.org/title/PCI_passthrough_via_OVMF#Prerequisites
  
kvm is amazing and using it I plan on making an ultimate 3-in-1 operating system in which I can develop programs, play games at near-native performance, and do all other computer stuff. 
the base layer will be Manjaro because it's based on Arch and all Arch packages work on it and the AUR is awesome. 
the Windows layer will be a Windows 10 Pro VM with GPU Passthrough so I can play all my games without worrying about compatibility. 
and an extra MacOS High Sierra layer just for the memes 
   
UPDATE 
   
![image](sadness.jpg)
  
After much research this just isn't viable until I have atleast a 1tb nvme ssd and a really REALLY fast cpu with atleast 16 threads. 
so this project is on hold until I get a super cool rig with high end components. 
motivation to put in effort so that I can achieve my dreams++
  
Update 2: you also need an additional monitor because the passthrough vm doesnt show on the primary monitor unless you're using a spice server which has a large performance overhead so why even bother becuase the entire point of this system is supposed to be close-to-native performance on virtual hardware. sighhhhhh 
  
(just in case)
https://github.com/mysteryx93/GPU-Passthrough-with-Optimus-Manager-Guide
  
Update 3: WE"RE COOKING 
  
![image](https://github.com/shahwaizse/lwm-triforce/assets/64956185/50b8d0dc-9260-4de3-baf1-a9fc63841ca8) 
 
  
https://gist.github.com/firelightning13/e530aec3e3a4e15885a10f6c4b7ae021?permalink_comment_id=4736891#setting-up-windows-1011-vm  
  
Looking Glass is a nice tool which on the surface seems to solve my single-monitor woes. have to dig more though  
  
UPDATE 4: GPU has been passed through less goooo
  
![image](https://github.com/shahwaizse/lwm-triforce/assets/64956185/330e7585-30c8-4b40-8c29-357e290eeeb3)  
  
Update 5: I keep getting the accursed Code 43 error which could mean a million different things and honestly I know what I must do but I don't know if I have the strength to do it.
