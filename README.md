# fileshare
Fileshare using the DewritoHub API

FileshareHelper.exe is a node app converted to exe with pkg and create-nodew-exe for making it run in the background. 

the EdFileshareLauncher.exe is a VBScript that is converted to an exe with VbsEdit and the program launches a bat script in the background that launches ED and the FileshareHelper, and when ED closes it kills the fileshare helper so you dont have to worry about it running in the background all time like a zombie process. the EdFileshareLauncher.exe also just closes right after it launches the bat script
