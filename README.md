# 1.1 Update !

You need to delete the previous files and download the new version. (See #Installation Notes)

What's new ?
- Changed the method of deleting the models
- Now comatible with Props Hospital by All_sor https://forum.fivem.net/t/release-hospital-props/151753 
The hospital came without any operation room or office, you can now use ymaps that need modified hospital props 
- better access to the elevator
- fixed crashes

# PillboxHospital-by-Jobscraft

What has changed? I cleaned the entire hospital. No more debris on the ground and no more destroyed walls... This modification took me around 6 month to find a way to clean it. After a few months, I realized that I had to learn 3dsmax and modify the game files.

# Installation Notes

- Download Zip and Uncompress Contents
- Put the "PillboxHospital-by-Jobscraft-master" folder in your /resources/ directory
- Edit your server.cfg adding   

			start PillboxHospital-by-Jobscraft-master

- Required Resource! bob74_ipl - https://github.com/Bob74/bob74_ipl/releases/tag/2.0.7c
- You need to edit the "base.lua" file located in /resources/bob74_ipl/gtav/base.lua
- Add the following lines to the end of the base.lua file
	
			-- Pillbox_Hospital-by-Jobscraft  
			RemoveIpl("rc12b_default")  
			RequestIpl("rc12b_hospitalinterior")  

[optional]  
Add doors to the hospital.  
https://github.com/jobscraft/PillboxHospital-doors

 

 3d modification for fivem
