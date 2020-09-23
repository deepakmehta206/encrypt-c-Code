**# encrypt-c-Code**

Hey every one I am here to describe you how to encrypt/obfuscate your c# code in easy way. Secure your c# code from reverse engineering.

·     first of all you have to convert your class file into dll file with the help of visual studio.

·     Go to create new project

![img](file:///C:\Users\Sparrow\AppData\Local\Temp\msohtmlclip1\01\clip_image002.jpg)

 

Then find a class library project

![img](file:///C:\Users\Sparrow\AppData\Local\Temp\msohtmlclip1\01\clip_image004.jpg)

​          create a class library project according to your project /.net framework version.

  **OR** 

·     you can also create dll file with the help of vs(Visual Studio 2019 Developer Command Prompt)

·     ![img](file:///C:\Users\Sparrow\AppData\Local\Temp\msohtmlclip1\01\clip_image006.jpg)

·     you have to go that location where your class file is exists and just type 

**csc /t:library /out:DllName.dll yourclassfile.cs**

AND BOOM your Dll file is created!!!!!! :)

after converted from class file into Dll. you have to download Crypto Obfuscator from 

https://www.ssware.com/cryptoobfuscator/obfuscator-net.htm

<img src="C:\Users\Sparrow\Desktop\vscmd.png" style="zoom:50%;" />

 after open the software looks like this now you have to Add your assemblies which is you dll or exe file choose the pre assemblies setting which type of encryption you want. and then set the output directory where you want to save the encrypted Dll.

if you want to check your dll is encrypted or not you have to download  ILspy from from Microsoft store or from https://github.com/icsharpcode/ILSpy

and check it out your Dll file is encrypted or Not ..........

Happy encrypt your code...