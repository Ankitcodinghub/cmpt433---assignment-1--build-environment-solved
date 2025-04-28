# cmpt433---assignment-1--build-environment-solved
**TO GET THIS SOLUTION VISIT:** [CMPT433 – Assignment 1- Build Environment Solved](https://www.ankitcodinghub.com/product/cmpt433-assignment-1-build-environment-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;77104&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT433 - Assignment 1- Build Environment Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Read the entire assignment before beginning!

Submit deliverables to CourSys: <a href="https://courses.cs.sfu.ca/">https://courses.cs.sfu.ca/</a>

&nbsp;

<h1>1.&nbsp;&nbsp; Establish Communication</h1>
<strong>Setup:</strong>

Complete the Quick Start Guide for the BeagleBone Green (on course website).

See the website for a list of help-documents/guides for this (and later) sections.

The assignment describes <u>what</u> to do; the help-docs describe <u>how</u> to do it.

Setup a Linux machine (or virtual machine) for doing your work this semester.

Have the target communicating with the host via the serial port using screen.

Have the target and host on the same Ethernet network (physical or Ethernet over USB). Note: If you have a typo in a command when capturing screen output (i.e., a screen capture to a text file), don’t worry about “correcting” it. Just repeat the command.

Commands to be executed in a Linux console on host PC are shown starting with $, on the target are shown with a #. These are not part of the command; they just represent the terminal prompt.

<h2>1.1&nbsp;&nbsp;&nbsp; Serial (TTL to USB) Connection</h2>
Capture the following output from the target’s Linux terminal over the serial port.

Hint: In screen, you can turn on logging by pressing CTRL+a, and then press H (capital). This will create a log file on the host in the folder you started screen from.

Display target’s internet configuration (<strong>ifconfig</strong>).

Ping the host and let in ping at least 3 times; press<strong> Control C</strong> to stop it:

# <strong>ping 192.168.7.1</strong>

(Note: The IP address must be the host’s IP; run <strong>ifconfig</strong> on the host to find address). &nbsp;Rename the log file to as1-targetViaSerial.txt

<h2>1.2&nbsp;&nbsp;&nbsp; Ethernet Connection</h2>
Perform the following commands on the host in a terminal:

Display the host’s internet configuration.

Ping the target and let in ping at least three times.

SSH to the target (change the IP to match the target):

<strong>$ ssh root@192.168.7.2</strong>

This will log you in as root, no password is required.

Perform a directory listing of the /proc directory.

Display the kernel’s version, up-time, and CPU info:

<strong># cat version</strong>

<strong># cat uptime</strong>

<strong># cat cpuinfo</strong>

Exit the SSH session using the <strong>exit</strong> command.

Copy the text of your session to a new file named as1-hostViaIP.txt

You should be able to select the text in the terminal and copy-and-paste it into a text file (try running gedit on the host to create the .txt file)

<h1>2.&nbsp;&nbsp; NFS and Custom Login Messages</h1>
<h2>2.1&nbsp;&nbsp;&nbsp; NFS Mount</h2>
Mount your host’s ~\cmpt433\public\ folder on the target using NFS. See the website for NFS guide.

Create a script in your target’s /root/ home directory <strong>named </strong><strong>mountNFS </strong>which mounts your NFS.

Hints:

Use echo to create the file, such as:

# echo Da Command To Mount Folder Goes Here &gt; daFileToSaveInto

Change the permissions on script to be executable:

# chmod +x daFileToRun

<h2>2.2&nbsp;&nbsp;&nbsp; Root File System Customization</h2>
Make the following changes to the target’s root file system stored in eMMC (on board):

Overwrite the /etc/hostname file with: yourSFUEmailAddress-beagle

Example: bfraser-beagle

Tip: View what the /etc/hostname file currently contains first, and make a backup copy (just in case!)

# cd /etc

# ls hostname

# cat hostname

# cp hostname hostname.bak

Tip: Use echo (as used in previous step) to change the contents of the hostname file. Change the hosts file:

# nano /etc/hosts

Change all mention of beaglebone to yourSFUEmailAddress-beagle

This will change the board’s Linux terminal prompt once you reboot the board. Reboot using the command:

# reboot

<h2>2.3&nbsp;&nbsp;&nbsp; ASCII Greeting</h2>
Change the root file system stored on the target to display an ASCII welcome message on boot.

There are three files that display messages at start-up:

/etc/issue: Shown only on the serial port before the user logs in.

/etc/motd:&nbsp;&nbsp; Shown only on the serial port after the user logs in.

/etc/issue.net: Shown only on SSH connection before the user logs in. Note: Does not support any escape sequences (as described below). First, create a short ASCII message:

Use a website such as: http://patorjk.com/software/taag/

Make the message include at least your first name. You may add anything else you like.

Pick a “font” which is readable and would fit on the terminal screen.

For the above website, click the “Test All” link on the left and pick a good one. Copy the art into a new text file named issue.net in your host’s shared folder:

~/cmpt433/public

Note: changing /etc/issue.net is optional for this assignment, but easy to do! Copy your new issue.net file to a new file name just issue

Edit issue and add at least one escape code to the file to display some interesting information.

List of escape codes can be found here: <a href="http://www.cyberciti.biz/faq/howto-change-login-message/">http://www.cyberciti.biz/faq/howto-change-login-message/</a>

In /etc/issue you’ll need to replace all the ‘\’ characters in your ASCII art with “\\” because ‘\’ is the start of an escape sequence. Note that SSH uses issue.net and does not support escape characters, so don’t change ‘\’ to ‘\\’ in that file, only in issue.

Using NFS, copy issue and issue.net from the host to your target’s /etc/ folder. You may want to first make a backup copy of the contents of /etc/issue and

/etc/issue.net on the target.

Log out, using the exit command, to see your new message.

If logging in via the serial port, you’ll see /etc/issue along with your extra escape characters.

If logging in via SSH, you’ll see /etc/issue.net which does not support escape characters. You’ll need to re-SSH into the board to see this message.

You may delete or rename the /etc/motd file to cleanup the boot messages on the serial port if you like.

<strong><u>&nbsp;2.4&nbsp; This Section’s Deliverables </u></strong>

The next section guides you through capturing the boot-up text, which will show these changes.

<h1>3.&nbsp;&nbsp; Hello world = Der-Finger-Poken &amp; Der-Lighten-Blinken</h1>
(“Moving the joystick, turning on lights”)

<h2>3.1&nbsp;&nbsp;&nbsp; Hello World</h2>
On the host, create a new directory for assignment 1:

$ cd ~

$ mkdir cmpt433/work/as1

Note: ~ expands to the user’s home directory, /home/brian in my case.

On the host, inside ~/cmpt433/<strong>public</strong>/, create a folder myApps/

This will hold your compiled programs where they can easily be run on the target.

Create a hello program in cmpt433/<strong>work</strong>/as1/ (in C not C++!) using printf() to display a message of the form:

“Hello embedded world, from Brian Fraser!” (Substitute in your name!) &nbsp;Create a makefile that compiles your application and places the compiled file to the cmpt433/<strong>public</strong>/myApps/ folder. Your makefile should be such that you can compile and deploy (place executable to the myApps/ folder) using the following single command:

$ make

Simple Makefile (you may modify as desired):

<table width="608">
<tbody>
<tr>
<td width="608">all:

arm-linux-gnueabihf-gcc -Wall -g -std=c99 -D _POSIX_C_SOURCE=200809L -Werror hello.c -o hello cp hello $(HOME)/cmpt433/public/myApps/
</td>
</tr>
</tbody>
</table>
<h2>3.2&nbsp;&nbsp;&nbsp; Use LEDs &amp; Read Joystick</h2>
Modify your hello program from above to also play the following LED and Joystick game.

<table width="614">
<tbody>
<tr>
<td width="614">Display hello-world welcome message

Continuously loop through the following:

1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Display user’s current score

2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Program selects a ‘target’ answer of either up or down.

If up, turn on BBG’s LED 0 (top one); If down, turn on BBG’s LED 3 (bottom one)

3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Wait until user moves joystick:

If left or right, then turn off BBG’s LEDs, display goodbye message, and exit app.

If up or down, then:

–&nbsp; display correct/incorrect message, update score, and

–&nbsp; if correct flash all LEDs on once for 0.1s

–&nbsp; if incorrect flash all LEDs on five times for 0.1s on 0.1s off

4.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Wait until joystick is released (so you don’t double trigger on one push).
</td>
</tr>
</tbody>
</table>
The LEDs you are turning on are on the BeagleBone, not on the Zen cape.

Your program must run without error even if some or all of the GPIO pins for the LEDs or the joystick are already exported for GPIO use.

You need <em>not</em> un-export any GPIO pins your program exports for the assignment.

Requirements:

Use a Makefile to compile your program on the host, and copy the executable to your NFS shared directory (~/cmpt433/public). Run the program via the terminal on the target.

Follow the LED and GPIO guides before writing the program.

Sample console output is shown below. Note that it does not show which LED is on, nor what the user input was. First and last line in capture are the terminal.

<table width="565">
<tbody>
<tr>
<td width="565"><strong>root@beaglebone:/mnt/remote/myApps#</strong> ./hello Hello embedded world, from Brian!

Press the Zen cape’s Joystick in the direction of the LED.

UP for LED 0 (top)

DOWN for LED 3 (bottom)&nbsp;&nbsp; LEFT/RIGHT for exit app.

Press joystick; current score (0 / 0) Correct!

Press joystick; current score (1 / 1) Correct!

Press joystick; current score (2 / 2) Correct!

Press joystick; current score (3 / 3) Correct!

Press joystick; current score (4 / 4) Correct!

Press joystick; current score (5 / 5)

Incorrect! 🙁

Press joystick; current score (5 / 6) Correct!

Press joystick; current score (6 / 7)

Incorrect! 🙁

Press joystick; current score (6 / 8)

Your final score was (6 / 8)

Thank you for playing! <strong>root@beaglebone:/mnt/remote/myApps#</strong>
</td>
</tr>
</tbody>
</table>
Hint: Good function design will save you a lot of time!

Create some initialization functions to initialize the joystick and LEDs.

Create some functions to give you high-level control of joystick and LEDs. For joystick, I suggest you create an enum to represent the four directions, plus a ‘no direction’. Then create a function which returns which direction the joystick is pressed. Note this won’t handle multiple directions at once, but that’s OK for this app.

Keep your file organized!

You are welcome to use multiple files (.c and .h files) if you like, but you need not. If you use one .c file, make sure you organize your functions inside the file well. You may want to use function prototypes so you can organize your functions in the way you think makes the most sense.

<h2>3.3&nbsp;&nbsp;&nbsp; Run it via eMMC</h2>
On the target, copy your blinking hello program to the root user’s home directory (/root/). This will make it available on the target even when you have not mounted the public folder via NFS.

On the target, edit the root user’s .profile file using the nano text editor. Add a call your hello program when the user logs in.

The .profile file is in the user’s home directory (/root/), and is a script that runs whenever the user logs in.

Launch nano to edit a file (such as .profile) with:

# nano .profile

On a new line, enter the full path of the program (such as /root/myFileHere). Hint: Have the call to hello be the last line in .profile. This will let the user skip the blinking at log-in (Ctrl-c) and still have the rest of the script execute. &nbsp;To exit nano (and save), press Ctrl+x, then type y (when asked to save the file), then press ENTER to select the existing file name.

You can check that the file was edited correctly by using cat to display the file. Note that file names starting with a period, such as .profile, are considered hidden by Linux and will not show up in a file listing. Use the -a option for ls to show all files:

# ls -a

Test your script by logging out and logging back in. Log out with: # exit

<h2>3.4&nbsp;&nbsp;&nbsp; This Section’s Deliverable</h2>
Create a tar.gz file named as1-helloWorld.tar.gz of your as1/ directory. Include at least your hello C source code and its Makefile.

In general, to create a tar.gz archive, use:

$ tar cvzf targetFileName.tar.gz sourceFolderName

Use the serial port (screen) to capture the output of the following actions. Save the output into a file name as1-bootTrace.txt:

Hint: Toggle logging within screen on or off by pressing Ctrl+a, and then H (capital, without Ctrl). This will log output to your home directory in a file screenlog.0. After you capture all the output rename the log file to the required .txt file name.

Note that if you press the arrow keys during your session it may insert escape characters into your capture which you should edit out before submitting. It may be best to not use the arrow keys if you can avoid it. &nbsp;Capture output of the following actions:

<ol>
<li>Reboot the board, and capture all the text shown on the serial port (text will be from uBoot, the Linux kernel, and the programs loaded from the root file system).</li>
<li>Login as root, which will execute your hello light-blinking program.</li>
<li>Play a couple rounds of the game and then exit the program using the joystick.</li>
<li>Mount your NFS shared directory using your script (previous section).</li>
<li>Use ls to display the contents of the shared directory mounted on the target which contains your program (likely /mnt/remote/myApps).</li>
</ol>
&nbsp;
