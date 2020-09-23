# encrypt-c-Code
Hey every one i am here to describe you how to encryupt/obfuscate your c# code in easy way. secure your c# code from reverse engineering.
1:- first of all you have to convert your class file into dll file with the help of visual studio.
    create a class library project
    or 
    you can also create dll file with the help of vs(visual studio cmd)
a) you have to go that location where your class file is exists and just type csc /t:library /out:DllName.dll yourclassfile.cs
    and boom your dll file is created.
