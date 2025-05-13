# cs211-assignment-3-bomb-lab-solved
**TO GET THIS SOLUTION VISIT:** [CS211 Assignment 3-Bomb lab Solved](https://www.ankitcodinghub.com/product/cs211-assignment-3-bomb-lab-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93354&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS211 Assignment 3-Bomb lab Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

The purpose of Programming Assignment 3 (PA3) is for you to become familiar with the x86 Instruction Set Architecture (ISA). The nefarious Dr. Evil has planted a slew of binary bombs on our machines. A binary bomb is a program that consists of a sequence of phases. Each phase expects you to type a particular string on stdin. If you type the correct string, then the phase is defused and the bomb proceeds to the next phase. Otherwise, the bomb explodes by printing BOOM!!! and then terminating. The bomb is defused when every phase has been defused. There are too many bombs for us to deal with, so we are giving everyone a bomb to defuse. Your mission is to defuse your bomb before the due date. Good luck, and welcome to the bomb squad!

2 Instruction

To download your bomb, go to:

http://assembly.cs.rutgers.edu:9102

Fill the form up with your NetID and your email address to get your bomb package. The file that you will get is in the format bombN.tar, where N is your bomb ID. If you havent downloaded it in the iLab machines, copy the file there and untar your bomb into your home directory.

You must do this assignment on one of the following ilab machines:

<pre>cd.cs.rutgers.edu
cp.cs.rutgers.edu
grep.cs.rutgers.edu
kill.cs.rutgers.edu
less.cs.rutgers.edu
ls.cs.rutgers.edu
man.cs.rutgers.edu
pwd.cs.rutgers.edu
rm.cs.rutgers.edu
top.cs.rutgers.edu
vi.cs.rutgers.edu
cpp.cs.rutgers.edu
pascal.cs.rutgers.edu
java.cs.rutgers.edu
perl.cs.rutgers.edu
basic.cs.rutgers.edu
python.cs.rutgers.edu
prolog.cs.rutgers.edu
assembly.cs.rutgers.edu
lisp.cs.rutgers.edu
</pre>
You can then untar the bomb with:

<pre>tar -xvf bombID.tar
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
It will create a directory bombID that should contain the following files: 1. bomb: The executable binary bomb

2. bomb.c: Source file with the bombs main routine

3. README: File with the bomb ID and extra information

Your job is to defuse the bomb. You can use many tools to help you with this; please look at the tools section for some tips and ideas. The best way is to use a debugger to step through the disassembled binary. The bomb has multiple phases. The phases get progressively harder to defuse, but the expertise you gain as you move from phase to phase should offset this difficulty. Nonetheless, the latter phases are not easy, so please dont wait until the last minute to start. The bomb ignores blank input lines. If you run your bomb with a command line argument, for example,

<pre>./bomb mysolution.txt
</pre>
then it will read the input lines from mysolution.txt until it reaches EOF (end of file), and then switch over to stdin (standard input from the terminal). In a moment of weakness, Dr. Evil added this feature so you dont have to keep retyping the solutions to phases you have already defused. To avoid accidentally detonating the bomb, you will need to learn how to single-step through the assembly code and how to set breakpoints. You will also need to learn how to inspect both the registers and the memory states. One of the nice side-effects of doing the lab is that you will get very good at using a debugger. This is a crucial skill that will pay big dividends the rest of your career.

IMPORTANT: Every time that the bomb explodes, you will lose 0.5 points. It is important that you use breakpoints and avoid those unnecessary explosions.

3 Checking your Work

We provided a webpage where you can check your work. Here you can access the scoreboard to verify how many points you have, up to which phase you have defused the bomb, and so on.

http://assembly.cs.rutgers.edu:9102/scoreboard

4 Tools

There are many ways of defusing your bomb. You can examine it in great detail without ever running the program, and figure out exactly what it does. This is a useful technique, but it not always easy to do. You can also run it under a debugger, watch what it does step by step, and use this information to defuse it. This is probably the fastest way of defusing it. We do make one request, please do not use brute force! You could write a program that 2will try every possible key to find the right one, but the number of possibilities is so large that you wont be able to try them all in time. There are many tools which are designed to help you figure out both how programs work, and what is wrong when they dont work. Here is a list of some of the tools you may find useful in analyzing your bomb, and hints on how to use them.

• gdb: The GNU debugger is a command line debugger tool available on virtually ev- ery platform. You can trace through a program line by line, examine memory and registers, look at both the source code and assembly code (we are not giving you the source code for most of your bomb), set breakpoints, set memory watch points, and write scripts. Here are some tips for using gdb.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;To keep the bomb from blowing up every time you type in a wrong input, youll want to learn how to set breakpoints.</li>
<li>– &nbsp;For other documentation, type help at the gdb command prompt, or type man gdb, or info gdb at a Unix prompt. Some people also like to run gdb under gdb-mode in emacs.</li>
<li>– &nbsp;The CS:APP Student Site has a very handy gdb summary (there is also a more extensive tutorial)
• objdump -t bomb: This will print out the bombs symbol table. The symbol table includes the names of all functions and global variables in the bomb, the names of all the functions the bomb calls, and their addresses. You may learn something by looking at the function names.

• objdump -d bomb: Use this to disassemble all of the code in the bomb. You can also just look at individual functions. Reading the assembler code can tell you how the bomb works. Although objdump -d gives you a lot of information, it doesn’t tell you the whole story.

• strings -t x bomb: This utility will display the printable strings in your bomb and their offset within the bomb. Dont forget, the commands apropos and man are your friends.
</li>
</ul>
</div>
</div>
</div>
