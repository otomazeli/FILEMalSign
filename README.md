# FILEMalSign
FILEMalSign is just a very simple script for know if a file is a malicious code. It uses a simple SHA256 hash database (malsignDB) that works together with the pyhton script (filemalsign.py). The information stored in the "malsignDB" file is very simple and is in plain text, so you could add your own information to detect malicious code following a simple syntax based on hash sha256 (to avoid collisions) and the AV nomenclature.

* NOTE: You need uncompress the file "malsignDB.7z". This have the signature database file "malsignDB".

I use the "MalwareIntelligence" nomenclature because it's based in an experimental project related with malicious code detection, so you can simply add the word "MALWARE" to complete the simple signature. At the moment it detect more of 500k of malicious code variants. Please, see the file "SIGN_CHANGELOG" for more details.

* Note that it isn't a malware scanner as a complete antivirus program. It's just a file identification focused in malicious code but on-demand.  

This script was born as part of a personal task where I simplely needed to check a large volume of files (multiplatform) to know quickly if they were detected as malicious. Obviously, I cann't be held responsible for any kind of misuse you give to this script.

* Support filetype tested: EXE, CPL, DLL, SCR, ELF, PDF, JAR, JS, RAR, ZIP. 
	*** In theory support all filetype format but, of course, maybe don't work with all files.
* I use the script in Ubuntu, Mac and Windows.

Usage syntax: ./filemalsign.py -o [filepath]

Request:
Colorama

** If you would like to collaborate in any way or would like report me any problem like FP, please just write to my an email.

jamieres-[at]-gmail-[dot]-com. 
@jorgemieres


