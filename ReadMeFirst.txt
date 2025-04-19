--------------------------------------------------------
Davi Rich   aka: Stalkerstein   long live S.t.a.l.k.e.r.
--------------------------------------------------------


    I have been retired for twenty four years, so out of boredom I wanted to learn some Python, 
or my wife might force me to paint the house again. I will be eighty years old this year in 2025.

    Linux was new to me and trying to remember all the commands was tedious so I thought that I
could learn some Python and create a useable program to run the commands. My program does not
run any programs that change the system, it just displays information to a text file or to the
terminal. The outputted text files will be in a desktop folder named LECC. This folder is 
created when the program starts. You can delete it because the program will recreate it. 

    I originally used Tk, then moved to PyQt5, then to PyQt6 and now PySide6. PySide6 is easier
to manage. I've been using lately Python 3.12, QtDesigner 6.4.2 & Pycharm 2025.1 (Community).

    The reason that I removed my program from github was because a couple of my friends didn't like
typing in the password all the time when using the program, there is enough of that using Linux. 

    I have changed the program to allow most of the programs to run without entering a password
except for a few programs that require it. The password is optional. Hence about ninty percent of
the programs can be used without requiring a password.

    Because of my age I am releasing my program as is at github. Anyone can use the code if they
want to, just mention me as the creator. I have tested as best that I could on about twenty five
different distros and a few different desktops. Out of all these distros I favor Mint and Parrot.

    Within the Python code file is more information for all to read. I know that my code is not
going to be the best, the gurus might laugh at it, but I tried, and the program does work.

    At github will be two 'tar.gz' files and an LECC.bin file and a ReadMeFirst file and images.
I created the LECC.bin file on Mint 22.1 using the below command with Nuitka 2.6.9:

/home/[name]/.local/bin/nuitka --standalone --onefile --follow-imports --plugin-enable=pyside6 LECC.py

    Sometimes a .bin file created on one distro might work on another distro. Using chmod 777 and
chmod +x on the .bin file should allow it to run.

    On the LECC.py menu line is Help and below that are the following: About, Notes, Commands and
Testing. Outputs has choices for the terminal or a text file. Notes explains how the program
works. Also on the Menu line is a choice of Styles (colors), and then URLs for DistroWatch and the
linux distro Forum, and finally License information. Make sure you read the Notes page.

P.S. The LECC.bin file is to big to upload. Best to run the .py & .ui files in PyCharm.

    



    

    



    

    
