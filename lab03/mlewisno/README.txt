Lab03 requires the use of a picture class. 

Make sure you get the picture.py file in this folder before starting the lab.

You need to put picture.py in the same folder with your lab files, 

and do "from picture import Picture" where you need it.

The current picture class might not be perfect and require changes later, 

so if you have any suggestions for improvement or want to report a bug, 

shoot me an email to szheng@oberlin.edu.



Also, to use picture.py you need to install PIL(Python Image Library) first.

For platforms other than Windows, you can download PIL from 

https://github.com/peter-fogg/pil-py3k/tree/master/PIL 

In the command line, go into your PIL folder, and then do "python setup.py install".

If you are using Windows, a simpler way to install PIL will be to use the .exe file from 

http://www.lfd.uci.edu/~gohlke/pythonlibs/#pil

If you have problems installing PIL, feel free to email me at szheng@oberlin.edu.


FAQ:

1. Q: Why do I get the error “global name Picture is not defined”?
   
   A: It is probably because you haven’t put the picture.py in the same folder with your program, 

      or haven't import Picture. At the top of your program, write "from picture import Picture". 

2. Q: Why can't I get any image displayed?

   A: If it doesn’t display any image, try running from IDLE instead of from the command prompt. 

3. Q: I'm using Windows and when I try to install PIL, it says python3.3 can't be found on the registry?

   A: Try a different version of .exe. There is one for amd64 and one for win32.

4. Q: ImportError: No module named 'PIL'?

   A: You haven't installed PIL or haven't installed it correctly.

5. Q: On Windows, when I try to install PIL, there is this "unable to find vcvarsall.bat" error. What should I do?

   A: Use the .exe file instead of the .zip file from the link. 

6. Q: On Mac, when I try to install PIL, I get a bunch of errors...

   A: Maybe your computer does not have the compiler necessary for installing libraries to Python. 

      Installing xcode before installing PIL should solve the problem. The link to xcode is 

      http://www.tech-recipes.com/rx/726/mac-os-x-install-gcc-compiler/ 

7. Q: I get errors when constructing the picture object from given height and width.

   A: Do Picture((width, height)) instead of Picture(width, height).

