## Training Day 1
**Topics:** Linux terminal basics, first Python script
**Time studied:** [fill in]

### Linux
**Goals**
- [x] Open a terminal from a cold start (no notes) and, from memory, run `whoami`, `pwd`, `ls`, `cd` into a folder, `pwd` again, then `cd` back home
- [x] Explain `pwd`, `cd` and `ls` in my own words

**Commands I learned**

| Command | What it does |
|---|---|
| `whoami` | Shows which user I'm logged in as |
| `pwd` | Print working directory: shows where I am in the file system |
| `cd` | Change directory: move from one directory to another |
| `cd ..` | Go up one level to the parent directory |
| `cd ~` | Go to my home directory |
| `cd /` | Go to the top of the file system (the root) |
| `cd -` | Jump back to the previous directory I was in |
| `ls` | List the contents of the current directory |
| `ls -l` | Long listing: shows permissions (read, write, execute), owner, size and date |

**To revisit:** the permissions shown by `ls -l` (read, write, execute for the owner, group and others). Covered in training days 8-14.

### Python
- Python doesn't show up as an app in Ubuntu. It's a command-line tool and comes preinstalled.
- Check the version with `python --version` (mine showed Python 3.14.4). Start Python with `python3`.
- Python 2 is retired. Python 3 is the current version.
- Shortcut to open a terminal in Ubuntu: Ctrl + Alt + T.
- Wrote my first script, `hello.py`, in nano, using `print()`.

### What I struggled with
- **Problem:** "No such file or directory" when saving my script to a folder named "Training Journey".
- **Cause:** the terminal uses spaces to separate a command from its arguments. `cd Training Journey` was read as `cd` with two arguments, `Training` and `Journey`, and neither exists.
- **Fix:** avoid spaces in folder names (use `-` or `_`), or wrap the name in quotes. Cloud and DevOps people usually use kebab-case (`training-journey`). I'm mixing hyphens and underscores while I learn.

### What I built
A short joke story in `hello.py` using `print()`. I ran it from the terminal, starting in my home directory and moving to my training folder with `cd`.

### Next session
- Linux: `mkdir`, `touch`, `cp`, `mv`, `rm`, `cat`, `man`
- Linux Journey "Grasshopper" section
- Python: keep practicing scripts




## Training Day 2
### Note:
- After an hour of learning and starting to begain my notes, I realized I will spend more time trying to recreate the format given by the AI model used to start this, that I would spend more time writing out my notes that actually studying. Not necessarily a bad thing, but it isn't the main goal of this. The goal of my notes is to show what I did to further my knowlege and what I learned from it. So, moving forward, my notes will be more casual.

**Topics:** Learning more basic Linux
**Time studied:** [1 hr]

### Linux
**Goals**
- [x] Start Labex Linux Journey course
- [x] Learn history and learn more about different Linux Distrobutions

**What I learned**

- The same story about how linux started that you read/hear/watch at the begining or any material that teaches the basics of linux.
- Learned about the Distributions and what they are best/created for.

## What I struggled with 
-Boredom... As a Tactile and kinesthetic learner, I learn by hands on. from what I was told, this will change and it will become more intereactive later. So I will continue with it.
      



## Training Day 3
### Note:
- I'm still learning and setting my standard as I go, so this format will keep changing as I figure out what works. On Day 2 my notes weren't as good because I went through the lesson first and then wrote them from memory. Today I tried typing notes as I learned, but it took too much time during the lesson and I wasn't able to finish it. Next time I'll jot quick notes on a notepad in my own words, then use Claude to organize them so they're easier for readers to follow. I take my notes in the default Ubuntu notes app and keep a running copy locally. I've also switched to LabEx's courses because the labs are hands-on and cover the same material as the other section, but fit my learning style better.

**Topics:** Linux command line
**Platform:** LabEx
**Skill tree:** Linux
**Course:** Quick Start with Linux
**Lab:** Your First Linux Lab
**Time studied:** [fill in]

### Linux
Reviewed `cd` and `pwd` (using `cd` to get to the right directory and `pwd` to confirm I was there), plus `echo` for displaying text.

**Commands I learned**

| Command | What it does |
|---|---|
| `>` | Output redirection: sends a command's output into the file named on the right (e.g. a `.txt` file). If the file already exists, it gets replaced, so check the destination first when working with important data |
| `date` | Prints the current date and time (weekday, date, time, time zone, year) |
| `date +` | The `+` lets me choose how and what information is printed |
| `%F` | Prints the date in ISO format (ISO = International Organization for Standardization) |
| `date +%F` | Prints the date as YYYY-MM-DD (year-month-day) |
| `cal` | Calendar: displays the current month's calendar |
| `expr` | Expression: does integer arithmetic, string manipulation and logical comparisons, mostly used inside shell scripts |
| `figlet` | Prints text in large letters made from characters/symbols |
| `figlet -f slant` | `-f` lets me choose a preset font; `slant` is a slanted font (like italics) |
| `clear` | [ timed out - Uncompleted |

**`expr` math operators**

| Operator | Operation |
|---|---|
| `+` | Addition |
| `-` | Subtraction |
| `/` | Division |
| `\*` | Multiplication |

**Note:** The terminal treats `*` as a wildcard. To use it as multiplication, put a backslash in front of it: `\*`. The lab also stressed that spaces matter, because the shell separates commands into words using spaces.

### What I struggled with
- **Problem:** The lab never explained what `expr` actually is.
- **Cause:** The lab focused on using it, not on what it means.
- **Fix:** Looked it up myself (integer arithmetic, string manipulation and logical comparison in shell scripts).

### What I built
- Saved the current date into `today.txt` using `>`, then read it back with `cat`.
- Saved the current month's calendar to a text file using `>`.
- Saved the result of 6 × 7 into `calculation.txt` using `>` (`expr 6 \* 7 > calculation.txt`), then opened it to see the answer, 42.

### Next session
- finish last section of lesson
- switch back to the training document used with training day 1. this will give me a day to learn something new, then through the repetition of the Linux-python-daily-plan.pdf document, to reinforce what I am learning.





## Training Day 4
### Notes:
- A busy couple of days with personal appointments threw off my sleep schedule, so today was a lighter, exploratory day. I downloaded a few terminal-learning apps from the app store (like Learn Terminal Fun) to play around with. First I finished the LabEx lab I never fully completed, then I started following the Linux & Python Daily Spiral Learning Plan (linux-python-daily-plan.pdf), which puts me on Day 2 for both Linux and Python. I plan to update my README to include the plan and how it's structured. I'm posting the Linux portion now and will come back for Python after some sleep.

**Topics:** Linux (directories and files), Python (variables and data types)
**Sources:** LabEx (Quick Start with Linux, Your First Linux Lab) and the Linux & Python Daily Spiral Learning Plan, Day 2
**Time studied:** [fill in]

### Linux
Finished the rest of the LabEx lab, then started Day 2 of the plan. Reviewed Day 1's commands (`whoami`, `pwd`, `cd`, `ls`) before adding anything new.

**Goals / Homework**
- [x] Create a folder called `linux_practice` in my home directory with three files inside it, using only the terminal
- [x] Repeat Day 1's full sequence from memory before doing today's homework

**Commands I learned**

| Command | What it does |
|---|---|
| `mkdir` | Make directory: creates a new folder in the file system. Can create multiple folders at once |
| `touch` | Creates an empty file. Can create multiple files at once |
| `nano` | Simple text editor: open a file, type a message, then save and exit (Ctrl+O to save, Enter to confirm, Ctrl+X to exit) |
| `cat` | Prints a file's contents to the screen, so I can preview a file after editing it |
| `chmod` | Changes permissions. Used it to make an executable file (`chmod +x`). Permissions get covered in full later in the plan |
| `rmdir` | Removes a directory |

**Practice (repeated 3-5 times)**
- Made folders, `cd` into them, and confirmed my location with `pwd`
- Created three different files with `touch`, then used `ls` to see them in the directory
- Opened files with `nano`, left a message, saved, exited, and used `cat` to preview

**What I forgot and how I remembered:** 
-between these two training materials of LabEx and the Daily plan doc, as well as other apps and open source infomation I look at when I have a chance. I didn't really forget anything but did trip up a few times between touch and cat for some reason.

### What I struggled with
- **Problem:** The `.txt` files I made in the LabEx lab were gone when I went back to finish it.
- **Cause:** The lab session timed out.
- **Fix:** Rebuilt them. It turned into a quick refresh of the earlier commands.

- **Problem:** I started building my own folder structure (a `US` folder with a folder for each state and city, each with a `.txt` file) instead of following the plan.
- **Cause:** I didn't want to clog my everyday file system and Desktop with folders and documents. so I tried to create the US one inside my own study work folder. but later decided against it and to stick to the plan.
- **Fix:** Deleted all of it, in case the plan builds on its own structure later. Lesson learned: follow the training doc. It did give me extra practice with `mkdir` (including several folders at once), creating files, and `rmdir`.

### What I built
- `home/linux_practice/practice/subfolder` with three files inside
- An executable file, made with `chmod`

### Side note for now (will delete later)
- appointments have disturbed my sleeping scheduled, so I am getting some sleep and will return later in hopes to finish python. 

### Python
**Goals / Homework**
- [ ] Update `about_me.py` to use variables and f-strings instead of hardcoded text in every `print()`
- [ ] Redo Day 1's practice from memory before starting (I'll note what I forgot, where and how I looked it up, and anything else I picked up)

**Concepts for today:** variables, data types (`str`, `int`, `float`) and f-strings.

[Python notes to fill in after the session]

### Next session
- [fill in]
