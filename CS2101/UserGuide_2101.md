# User Guide

![Logo](../img/logo.jpg)

## Introduction

Hello! Thank you for choosing to use PulsePilot!

Our team appreciates that you are giving our space-themed health application a try, and we hope that it helps you document your recovery journey better and bounce back from whatever injury you are facing.

This document serves as the **User Guide** of PulsePilot, designed to help you (an injured athlete) learn what PulsePilot is about, our motives, how to install it and how to use it.

Learning to use software can be daunting. Thus, this guide was created for **non-technical users**, helping you unleash PulsePilot to its fullest potential! That being said, we assume that you know how to use the basic features on your computer, such as **downloading files or copying and pasting text from one program to another**. 

Once again, we hope our application helps you, and thank you for choosing PulsePilot, and we hope you recover as fast as possible!

## Contact Us

If you have any queries with the guide, our application, or even life in general,  please feel free to reach out to our project director **Justin Soh** at [+65 91234567](https://www.youtube.com/watch?v=eBGIQ7ZuuiU)!

---

## Table of Contents

* [How to use this guide](#how-to-use-this-guide)
  * [Glossary Usage](#glossary-usage)
  * [Blocks](#blocks)
* [About PulsePilot](#pulsepilot)
  * [What is it?](#what-is-it)
  * [Origins](#origins)
* [Command Line Interface](#command-line-interface)
* [Installation](#installation)
* [PulsePilot Commands](#pulsepilot-commands)
* [Experienced User Guide](#experienced-user-manual)
* [Command Summary](#command-summary)
* [Frequently Asked Questions](#frequently-asked-questions)
* [Glossary](#glossary)

---

## How to use this guide

Before we delve into the content of what is PulsePilot and how to use it, we want to let you know and get familiar with the styling used in this guide, so that this guide can help you better!

### Glossary Usage

This guide may have difficult to understand technical jargon or terms used. Fret not! We understand that seeing such terms can be daunting to someone not familiar with it.

As such, our team has created a **Glossary** for you to refer to when reading this guide! It serves as a mini-dictionary, for you to read a definition and quickly go back to wherever you were.

Technical terms are marked in **italicised blue** [*like this*]()! When you click on it, it brings you to the glossary. Each term in the glossary also contains a 'Go back' button, and clicking on that returns you to where you originally were. This is to create a seamless reading experience for you! 

Note that only **the first instance** of a term will be hyperlinked!

Give it a try with the term: [*Object-Oriented Programming*](#glossary).

The blue phrases known are also known as [*hyperlinks*](#glossary).

Non-italicised hyperlinks [like this]() are used to bring you to different parts of the document.

For example, **the one below to bring you back to the table of contents on top!**

###### [Back to table of contents](#table-of-contents)

---

### Blocks

There are 3 different kinds of **blocks**, denoted using different **icons** to bring things to your attention.

> 💡 This is an **information** block. It is used to highlight **additional** details that you might be interested in!

> ⚠️ This is a **warning** block. It is used to highlight key information that **may** be useful for you!

> ❗ This is an **important** block. It contains information that you **MUST READ**! Take note of these!

###### [Back to table of contents](#table-of-contents)

---

## PulsePilot

### What is it?

PulsePilot is an application made by 6 computing students from the National University of Singapore (NUS) that helps you (the user) document each stage of your recovery journey better! More specifically, it was coded in [*Java*](#glossary).

The application is built for **both** healthcare professionals and patients. Using PulsePilot, patients can better record their recovery progress from an injury, as well as general well-being. 

Healthcare professionals on the other hand would use PulsePilot to view the information that a patient has logged, allowing them to better keep tabs on their patients' recovery status outside the hospital.

At the time of writing, you can do the following with PulsePilot:

  - Keep training logs of **both run and gym** workouts.
- Store information of your **past menstrual cycles and make predictions of future cycles**.
- Record past or present **medical appointment** information.
- Keep a log of your **Body Mass Index (BMI)**.  

More details about how to [install](#installation) and use [PulsePilot](#pulsepilot-commands) are covered below!

###### [Back to table of contents](#table-of-contents)

---

### Origins

On top of being NUS Computing students, our team members are all competitive athletes who have had past injuries and hence dealt with the healthcare system in Singapore.

We came together and realised that one common denominator was our unhappiness with the level of service received from the healthcare system when we were injured. We want to use our experience and knowledge about creating software learned from our university course to better the lives of all athletes in Singapore.

We have done extensive research onto this problem, as well as received testimonials from both varsity and national-level athletes about their recovery experiences. In general, they too were unhappy with the level of service received.

The 2 main problems identified from our study were:

1. Poor communication between **healthcare professionals and patients** inhibiting medical progress:
 This can be caused by the long waiting periods in between sessions, by a patient seeing more than 1 specialist at a time or from the specialist having too many patients to monitor.

2. **Data Fragmentation**:
  As mentioned above, a patient can see many specialists, thus resulting in their information and hence recovery status being **spread out across different clinics, hospitals and people**. There is **no centralised system** for doctors to read patient data and for patients to update all doctors simultaneously.

The above problems gave rise to PulsePilot, the guide for which you are reading right now! PulsePilot was designed with both patients and healthcare professionals in mind to solve the 2 main problems identified above!

We hope that PulsePilot can bridge the information gap between you and your doctor, and we wish you a speedy recovery. D

> ❗ This application is still in [*beta phase*](#glossary). As such it is not complete and more features will be added in future versions. Stay tuned for updates!

###### [Back to table of contents](#table-of-contents)

---

## Command Line Interface

> 💡 This section explains what a [*Command Line Interface (CLI)*](#glossary) is. If you are already familiar with this, please feel free to move on to the [installation section](#installation) .

> ⚠️ For **inexperienced** users, if you are not familiar with what the CLI is, keep reading this section. PulsePilot is built to be run using the CLI, and its [*commands*](#glossary) are also entered through the CLI!

Let us begin exploring the [*Command Line Interface (CLI)*](#glossary)! This section is further broken down into the 2 most common operating systems: Windows and macOS. Remember that PulsePilot can be run on **any operating system with Java installed**!

Here is a sub table of contents, so you can navigate through this section easily:

* [Windows](#windows)
  * [Launching `cmd.exe`](#launching-cmdexe)
  * [Windows Commands](#windows-commands)
* [MacOS](#macos)
  * [Launching `bash`](#launching-bash)
  * [MacOS Commands](#macos-commands)

###### [Back to table of contents](#table-of-contents)

---

### Windows

#### Launching `cmd.exe`

Let us first begin with launching the command line for Windows. The name of this program is `cmd.exe`!

To do so, firstly, hit the <kbd>![winlogo.png](img_2101%2Fwindows%2Fwinlogo.png) Windows</kbd> key on your keyboard to bring up the start menu:

![Windows Start](img_2101/windows/windows_start.png)

Afterward, type `cmd` or `Command Prompt` into the search bar above, and there should be 1 program found called the '**Command Prompt**'.

![Finding cmd.exe](img_2101/windows/finding_cmd_exe.png)

Go ahead and click on that, and a _black_ window should pop up on your screen looking similar to this:

![Launching cmd.exe](img_2101/windows/windows_cmd_exe.png)

Congratulations, you have successfully launched the CLI for Windows!

The string `C:\Users\rouvi` is the current [*directory*](#glossary) that you are in! This means that currently, the [*CLI*](#command-line-interface) is within the `C:\Users\rouvi` folder of the computer.

> ❗ The directory and CLI for you may look different from the one shown in the guide! This is **normal** as the guide was created using a different computer. As long as the top of the window shows '**Command Prompt**', you are good to go!

You can type different things into the CLI, and press <kbd>Enter</kbd> to make your computer read the input and process it as a command.

For the example below, I typed a `hello` and hit <kbd>Enter</kbd> to make the compute read it.

![Typing Commands](img_2101/windows/sample_windows_type.png)

`hello` is not a valid command to use with `cmd.exe`, and your computer will let you know it is not a recognised command as shown in the image above.

Read the next section to learn some basic commands!

###### [Back to Command Line Interface](#command-line-interface)

###### [Back to table of contents](#table-of-contents)

---

#### Windows Commands

##### Changing Directories

There are many commands in Windows, but this guide will cover the basic few you need to use PulsePilot.

The first command is `cd`, short for **change directory**. It changes the **current** directory to the specified one. The format to use it is `cd <DIRECTORY>`, where `<DIRECTORY>` is something you pick!

For example, suppose I want to go to the `cli_demo` folder from my current directory. I would type the following:

![cd](img_2101/windows/cd.png)

Note how `C:\Users\rouvi` now has `\cli_demo` appended to the back. This means that the directory has been changed successfully.

If you `cd` to a directory that does not exist, your terminal will let you know it cannot find such a directory:

![cd error](img_2101/windows/cd_error.png)

If you want to go 'back' one directory, use `cd ..`.

> 💡 `..` means the previous directory.

![cd ..](img_2101/windows/cd_back.png)

##### List Directory Contents

Now, suppose you want to view files a directory has within it. You can use `dir` to do so. 

For example, I want to view what files are within the `cli_demo` folder. I would first `cd` to the `cli_demo` folder, and then use `dir` to view the output:

![cd then dir](img_2101/windows/cd_dir.png)

This would print out all the folders within the directory. In the `cli_demo` directory, I have a `hello.txt` and a `pulsepilot.txt` file. 

I also have another folder within `cli_demo` called `another_directory`. Your computer differentiates between files and directories using the `<DIR>` string printed before the name of the file or folder.

That is all the commands you need to know to navigate through the Windows CLI and use PulsePilot! To summarise:

* `dir` - Lists the files and directories in the current directory.
* `cd <DIRECTORY>` - Changes the current directory to the specified one.

###### [Back to Command Line Interface](#command-line-interface)

###### [Back to table of contents](#table-of-contents)

---

### MacOS

#### Launching `Terminal`

On macOS, the default command line interface is called the **Terminal**, which uses the `Bash shell`. 
To launch the **Terminal**:

1. To begin searching for **Terminal**:
   - Open the Launchpad: The Launchpad is the grid of app icons on your Mac's Dock. You can usually find it in the bottom of your screen.
   
   ![Launchpad](img_2101/macos/launchpad.png)

   - Open the Spotlight Search Bar: Hit <kbd>⌘ command</kbd> + <kbd>Spacebar</kbd> on your keyboard at the same time to bring up the Spotlight Search Bar.

   ![Spotlight Search Bar](img_2101/macos/spotlight_search.png)


2. Search for `Terminal`: 
   - In the Launchpad: In the Launchpad search bar, type `Terminal` and you should see 1 program found called the '**Terminal**'. Click on it to launch **Terminal**.
   
   ![Terminal in Launchpad](img_2101/macos/launchpad_terminal.png)

   - In the Spotlight Search Bar: type `Terminal` and you should see 1 program found called the '**Terminal**'. Click on it to launch **Terminal**.
   
   ![Terminal in Spotlight Search Bar](img_2101/macos/spotlight_terminal.png)


3. Open the **Terminal** App: After clicking on the **Terminal** app icon to launch the **Terminal** application, you should now see a _white_, _grey_ or _black_ window pop up on your screen looking similar to this:

![Terminal](img_2101/macos/terminal.png)

Congratulations, you have successfully launched the CLI for MacOS!

The [string](#string) `~` in `l5z@L5Z-MacBook-Air ~ %`is the current [*directory*](#glossary) that you are in! This means that currently, the [*CLI*](#command-line-interface) is within the `~` directory (or folder) of the computer.
This string will be **updated** to always reflect the directory you are currently in while navigating. 

In the example below, I am currently in the `Desktop` directory.

![Terminal Directory String](img_2101/macos/cd_desktop.png)


> ❗ The directory and CLI for you may look different from the one shown in the guide! This is **normal** as the guide was created using a different computer. As long as the top of the window shows '**zsh**', you are good to go!

You can type different things into the CLI, and press <kbd>Enter</kbd> to make your computer read the input and process it as a command.

For the example below, I typed a `hello` and hit <kbd>Enter</kbd> to make the compute read it.

![Typing Commands](img_2101/macos/sample_mac_type.png)

`hello` is not a valid command to use with `Terminal`, and your computer will let you know it is not a recognised command as shown in the image above.

Read the next section to learn some basic commands!

###### [Back to Command Line Interface](#command-line-interface)

###### [Back to table of contents](#table-of-contents)

---

#### MacOS Commands

##### Changing Directories

List Directory Contents (ls): The ls command lists the files and folders in your current directory.
To use it, simply type ls and press Enter.
This will display all the items in your current directory.
Show Image
Change Directory (cd): The cd command allows you to change your current directory.
To change to a different directory, type cd <directory-name>, where <directory-name> is the name of the directory you want to navigate to.
For example, to change to the "Documents" folder, you would type cd Documents.
To go back to the previous directory, you can use cd ...
Show Image
Clear the Screen (clear): If the Terminal screen becomes cluttered, you can use the clear command to clear the screen.
Simply type clear and press Enter to clear the Terminal window.

The macOS Terminal allows you to enter and execute Bash commands.

##### List Directory Contents

**List Directory Contents (`ls`)**: The ls command lists the files and folders in your current directory.

Here are some common Bash commands you can use in the macOS Terminal:

* `ls` - Lists the files and directories in the current directory
* `cd <DIRECTORY>` - Changes the current directory to the specified one
* `clear` - Clears the screen of the Terminal


###### [Back to Command Line Interface](#command-line-interface)

###### [Back to table of contents](#table-of-contents)

---

## Installation

Now that you are familiar with the CLI, it is time to install Java and PulsePilot!

The installation for Java is different for Windows and macOS computers. However, the installation and launching of PulsePilot is the same for both operating systems!

* [Installing Java](#installing-java)
* [Installing and Launching PulsePilot](#installing-and-launching-pulsepilot)

### Installing Java

> 💡 If you already have Java 11 installed, feel free to skip to the [next section](#pulsepilot-commands) to learn about the commands for PulsePilot.

A specific version of Java will be required for PulsePilot, thus this part of the guide will bring you through the installation of Java 11.

A guide to install Java can be found [here](https://nus-cs2030.github.io/1920-s2/contents/guides/settingUpJava.html), as many other NUS modules use a similar version of Java for their projects.

>❗Although the website says it is for CS2030 from a previous semester, the steps are the same.

To ensure that you have the correct version of Java installed, launch the CLI (either `cmd.exe` or `bash`) and run `java --version`.

As long as the output shows `java 11` is installed, it is correct. The specific version 


#### Java for Windows


To install Java on your computer, you can follow these steps:

Visit the official Java website (https://www.java.com/en/download/)
Download the appropriate Java installer for your operating system (Windows)
Run the installer and follow the on-screen instructions to complete the installation

![Java Version](img_2101/installation/java_version.png)


###### [Back to Installation](#installation)

###### [Back to table of contents](#table-of-contents)

---


### Installing and Launching PulsePilot

> 💡 If you already have PulsePilot installed, feel free to skip to the [next section](#pulsepilot-commands) to learn about the commands for PulsePilot.

PulsePilot can be installed from our team's [*GitHub*](#glossary) repository [here](https://github.com/AY2324S2-CS2113T-T09-4/tp/releases/tag/v2.1).

The screen should have the following hyperlinks as shown below, and clicking on `pulsepilot.jar` will download the application to your Downloads folder.

![Downloading PulsePilot](img_2101/installation/download_pulsepilot.png)

Afterwards, launch the CLI, `cd` to your Downloads folder, and run `java -jar pulsepilot.jar`. If Java has been installed correctly, and you are in the correct directory, PulsePilot will launch successfully.

Your terminal should look like this below, with PulsePilot asking for your name.

![Launching PulsePilot](img_2101/installation/launch_pulsepilot.png)

> 💡 PulsePilot is spaced themed, thus the space terms in the introduction it displays on screen! 🚀🚀

> ❗ This process is the exact same for **both Windows and macOS!**

###### [Back to Installation](#installation)

###### [Back to table of contents](#table-of-contents)

---

### Common Problems

> 💡 If you do not face any issues with launching PulsePilot, feel free to skip to the [next section](#pulsepilot-commands) to learn about the commands for PulsePilot.

This section will address some common problems users will face.

#### Wrong Directory

When attempting to launch `pulsepilot.jar` from the wrong directory, this error will appear:

![Wrong Directory](img_2101/windows/wrong_dir.png)

This means that `pulsepilot.jar` is **not within your current directory**. To remediate this, use `dir` to check for the files present within your current directory.

If you are in the right directory, `pulsepilot.jar` should appear like so:

![Correct Directory](img_2101/windows/correct_dir.png)

##### Windows Fix

To fix this, do the following:

1. Find where `pulsepilot.jar` is within your machine using the [*File Explorer*](#glossary).

2. Right click on it and click on **Properties**.
  ![Windows Properties](img_2101/windows/properties_windows.png)

3. A separate window will appear with additional data for `pulsepilot.jar`. Copy the value of the **Location** part of the Properties window using <kbd>Ctrl + C</kbd> or highlighting the text, right-clicking it and selecting **Copy**.
  ![Finding Windows Path](img_2101/windows/windows_property_path.png)

4. Once copied, open the CLI for your device, and type `cd` and hit the <kbd>Spacebar</kbd> **once**, then paste the **Location** value you just copied using <kbd>Ctrl + V</kbd>. Then, hit <kbd>Enter</kbd>. You should see that you are now in the right directory, and use `dir` to verify that `pulsepilot.jar` is within this current directory.
  ![Right Directory](img_2101/windows/right_directory.png)

5. Continue to launch PulsePilot using `java -jar pulsepilot.jar`.

##### macOS Fix

After installing Java, you can install PulsePilot by following these steps:

Download the latest version of the PulsePilot application from the provided source
Extract the downloaded files to a directory on your computer
Open the Command Prompt (Windows) or Terminal (macOS) and navigate to the directory where you extracted the PulsePilot files
Run the PulsePilot application by typing the appropriate command (e.g., `java -jar pulsepilot.jar`)

###### [Back to Installation](#installation)

###### [Back to table of contents](#table-of-contents)

---

## PulsePilot Commands

Now that Java and PulsePilot is up and running on your computer, it is time to learn how to use PulsePilot via its implemented commands and [*flags*](#glossary).

> ⚠️ For **experienced** users, if this is not your first time using a CLI application or PulsePilot, feel free to skip ahead to the [experienced user manual](#experienced-user-manual)! If not, please continue reading!

* [PulsePilot Text Style](#pulsepilot-text-style)
* [Creating Your Profile](#creating-your-profile)
* [Viewing Help](#viewing-help)
* [Workout](#workout)
  * [Add Run](#add-run)
  * [Add Gym](#add-gym)
* [Health](#health)
  * [Add Period](#add-period)
  * [Add BMI](#add-bmi)
  * [Add Appointment](#add-appointment)
  * [Make Period Prediction](#make-period-prediction)
* [View History](#view-history)
* [View Latest](#view-latest)
* [Delete Item](#delete-item)
* [Storage of Data](#storage-of-data)
* [Exit](#exit)

### PulsePilot Text Style

The text in the step-by-step guide have been colour coded to help you better understand the commands, as it can get a bit confusing!

There are 3 colours used in the guide: <u>White</u>, <span style="color:red;">red</span> and <span style="color:green;">green</span>, each used for a different kind of text:

![Colour Coded Text](img_2101/pulsepilot_commands/colour_code.png)

- A response is merely a message from the bot.
- An error indicates that the bot has detected some invalid input from you. Read the error messages to find out what's wrong!
- Your input represents the command **you** type and press 'Enter' for PulsePilot to use!

> ❗If you are not seeing colours on your screen, and instead see **odd characters** like `[` or `<-`, please read our [*troubleshooting guide*](#odd-characters-on-screen) for this issue!

> ❗The colours on your own screen may be different, or it may not even be colour-coded at all. The colours are just visual cues for **this guide**!


###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Creating Your Profile

When you first run PulsePilot, it will prompt you for your name as follows:

![PulsePilot Intro](img_2101/pulsepilot_commands/induction/pulseintro.png)

You can enter your real name or an alias. PulsePilot only checks that you enter **[*alphanumeric*](#glossary) characters and spaces**. For example, `Justin Soh` is a valid name!

![Valid Name](img_2101/pulsepilot_commands/induction/valid_name.png)

After setting your name, **you are ready to use PulsePilot**!

> ❗Entering usernames that have non-alphanumeric characters, such as `;` or `|` will trigger an error!
> 
>  ![Invalid Name](img_2101/pulsepilot_commands/induction/invalid_name.png)
> 
> If this happens, not to worry! You can simply **re-enter a valid name** and PulsePilot will continue to work normally.
>
> ![Re-enter name](img_2101/pulsepilot_commands/induction/enternameagain.png)

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Viewing Help

This command displays the help message, which has information about all the other commands in PulsePilot.



1. When you enter `help`, PulsePilot prints out the help message.

![Help Command](img_2101/pulsepilot_commands/help/help_cmd.png)

> 💡 You can use this **as many times as you need** to get a quick summary for all the commands!

> ❗ Having extra characters after the first `help` word will be ignored! `help me` and `help` both print the same output with no issues.

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Workout

Being a health-tracking application, PulsePilot can record Run and Gym sessions. This is implemented via the `workout` command.

There are 2 types of exercises that can be recorded, denoted using the `/e:` flag.

- To add a run session, use `workout /e:run`.
- To add a gym session, use `workout /e:gym`.

There are details and flags required from you, which will be covered below.

---

#### Add Run

> 💡PulsePilot automatically calculates the pace of your run for you in minutes/km (i.e. `5.00/km`). This helps you track your progress better!

Here are the details required from you, and the required flag for PulsePilot to know which detail is being specified in your input.

| Detail     | Description                                                       | Flag Used | Limitations                                                                                                                                                                  |
|------------|-------------------------------------------------------------------|-----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `distance` | The distance ran in **kilometres**.                               | `/d:`     | Must be a **2 decimal point positive number** such as `5.15`. <br> Must be **at least** `0.01`, and is **capped at** `5000.00`. </br>                                        |
| `time`     | The time taken for the run.                                       | `/t:`     | Must be in either `MM:SS` or `HH:MM:SS` format. <br> Must be **at least** `00:01`, and is capped at `99:59:59`. </br>                                                        |
| `date`     | The date of the run. <br>This is an **OPTIONAL** parameter. </br> | `/date:`  | Must be in `DD-MM-YYYY` format. <br> Date specified **cannot be after today's date**. (i.e. If today is `10-04-2024`, specifying `11-04-2024` will trigger an error!)  </br> |

> ❗ The `date` parameter is **OPTIONAL**. Not specifying one results in it being recorded as `NA` within the bot, and it is okay!

> ❗ If the `HH` field in `time` is not needed and set to `00`, **an error message will be printed!**

The following example will cover how to add a run step-by-step.

1. Suppose a user wants to add **two** runs:

   - The first is a  **5.50km** run completed in **25 minutes and 12 seconds** on **7 March 2024**.
   - The second is a **20km** run completed in **2 hours, 13 minutes and 37 seconds** without a date.

2. Let's put the **first** run into the correct format with flags:

  - A **5.50km** run is specified using the `distance` flag via `/d:5.50`.
  - **25 minutes and 12 seconds** is specified using the `time` flag via `/t:25:12`.
  - **7 March 2024** is specified using the `date` flag via `/date:07-03-2024`.
3. Putting it together, the full command is:

   <code style="color: #D85D43;">workout /e:run /d:5.50 /t:25:12 /date:07-03-2024</code>
  
4. Entering it into the bot results in this output:

    ![Add first run](img_2101/pulsepilot_commands/run/add_run1.png)

5. Now, let's add  the **second** run:

  - A **20km** run is specified using the `distance` flag via `/d:20.00`.
  - **2 hours, 13 minutes and 37 seconds** is specified using the `time` flag via `/t:02:13:37`
  - **No date** is given, so we can leave the `date` blank.

6. The full command for the second run is:

    <code style="color: #D85D43;">workout /e:run /d:20.00 /t:02:13:37</code>

7. Entering it into the bot shows the following:

    ![Add second run](img_2101/pulsepilot_commands/run/add_run2.png)

8. Congratulations, you have added your first 2 runs to PulsePilot!

##### Error Messages

> ❗ This is just one example of invalid input. We will not cover the full list of errors here.

Adding an incorrect flag will cause the command for adding a run to be **invalid** and PulsePilot will not add anything. 

For example, if you used `/time:` instead of `/t:`

![Error in Flag](img_2101/pulsepilot_commands/run/run_error.png)



###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

#### Add Gym

idiot guide here.

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Health

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

#### Add Period

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

#### Add BMI

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

#### Add Appointment

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

#### Make Period Prediction

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### View History

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### View Latest

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Delete Item

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Storage of Data

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Exit

###### [Back to PulsePilot Commands](#pulsepilot-commands)

###### [Back to table of contents](#table-of-contents)

---

### Experienced User Manual

> ❗This guide is for **experienced** users, made to be briefer without much step-by-step demonstrations. There is **NO colour-coded text here** to guide you!
>
> **Only proceed if you know what you are doing!**

> ❗If you are **not** experienced, please head to our step-by-step guide for PulsePilot [here](#pulsepilot-commands).

* [User Induction](#user-induction)
* [Workout: Run](#workout-run)
* [Workout: Gym](#workout-gym)
  * [Adding Gym Stations](#adding-gym-stations)
* [Health: BMI](#health-bmi)
* [Health: Period](#health-period)
* [Health: Appointment](#health-appointment)
* [History](#history)
* [Latest](#latest)
* [Delete](#delete)
* [Help](#help)
* [Exit](#exit)

## User Induction

1. When you first run the PulsePilot application, the bot will prompt you to enter your `name` to create a new user profile.
   - Your `name` can only contain **alphanumeric characters (letters and numbers) and spaces**.
   
   > ❗ **WARNING:** If you enter a name that does not follow this convention, the bot will display an error message and prompt you to try again.

    ![Non-compliance of naming convention](../img/output/wrong_username.png)

2. After entering a valid `name`, the bot will create a new user profile associated with your `name`. 
This profile will be used to store all your health and workout data. 
3. Once your user profile is created, you can start using the various commands in PulsePilot to track your progress and health.
   - You may enter commands after receiving this message prompt:
     
      ![Accepting commands](../img/output/accepting_commands.png)
4. All your data will be saved and associated with your user profile
   - You can continue tracking your information across multiple devices. Find out more [here](#frequently-asked-questions).

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

## Commands

### Workout: Run

Adds a new run session to track.

Format: `workout /e:run /d:DISTANCE /t:TIME [/date:DATE]`

* `DISTANCE` is a **2 decimal point positive number** (i.e. `15.24`) representing the distance ran in **kilometers**.
* `TIME` is in `[HH]:MM:SS` format (i.e. `25:30`). The `HH` representing hours is **optional**.
* `DATE` is in `DD-MM-YYYY` format (i.e. `19-03-2024`). The date is **optional**, and if not specified, defaults to `NA`.

> ⚠️ If `HH` is set to `00`, the bot will throw an error. Please use `MM:SS` if the `HH` field is not needed!

> ⚠️ Date specified cannot be later than the current date!

Examples:
- `workout /e:run /d:5.15 /t:25:03 /date:25-03-2023`
- `workout /e:run /d:5.15 /t:25:03`

Expected Output:

![Adding Runs](../img/output/adding_runs.png)

> ⚠️ **Minimum and Maximum inputs:**
> Maximum Pace Value: 30:00/km, Minimum Pace Value: 1:00/km
> Maximum Run Time: 99:59:59, Minimum Run Time: 00:01
> Maximum Distance: 5000.00km, Minimum Distance: 0.01km
> 
> **Note that exceeding these bounds will trigger an error!**

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Workout: Gym

Adds a new gym session to track.

Format: `workout /e:gym /n:NUMBER_OF_STATIONS [/date:DATE]`

* `NUMBER_OF_STATIONS` is a **positive integer of at least 1** representing the number of stations for one Gym session.
* `DATE` is in `DD-MM-YYYY` format (i.e. `19-03-2024`). The date is **optional**, and if not specified, defaults to `NA`.

> ⚠️ Date specified cannot be later than the current date!

> ⚠️ Please input positive integers for `NUMBER_OF_STATIONS` without leading zeros. Entering a number with a leading zero, such as `01`, will trigger an error.

Examples: 
- `workout /e:gym /n:2 /date:25-03-2023`
- `workout /e:gym /n:4`

###### [Back to table of contents](#table-of-contents)

#### Adding Gym Stations

Upon entry of the `workout /e:gym` command, the bot will prompt for further details for each station done:

Format: `STATION_NAME /s:SET /r:REPS /w:WEIGHT`

* `STATION_NAME` is a **string**  representing the name of the gym station.
* `SET` is a **positive integer**  representing the number of sets done for one station.
* `REPS` is a **positive integer**  representing the number of repetitions done for one station.
* `WEIGHT` is a **list of positive numbers** separated by commas. It represents the weights used for all the sets in the station.

> ⚠️ `STATION_NAME` must always be the first parameter. The order of the other parameters can be in any order. `STATION_NAME` can **only contain letters and spaces**, and can be up to **25 characters long**.

> ⚠️ `WEIGHT` must be in **multiples of 0.125 KG**! This is because the minimum weight increment in a gym is 0.125kg. Example `bench press /s:2 /r:10 /w:10.333,12.5` is not valid as 10.333 is not a multiple of 0.125kg.

> ⚠️ Note that the **number of weights must equal to the number of sets**! For example, if you have done 2 sets at 10 kg, PulsePilot still expects 2 weights to be specified like this `squats /s:2 /r:5 /w:10.25,10.5`.

> ⚠️ Please input positive integers for `SETS` and `REPS` without leading zeros. Entering a number with a leading zero, such as `01`, will trigger an error.


Examples:
- `bench press /s:2 /r:4 /w:10,20`
- `squat /r:2 /s:2 /w:10.5,20.5`

Expected Output:

![Adding Gyms](../img/output/adding_gym.png)

> ⚠️ **Minimum and Maximum inputs:**
> Minimum Weight: 0kg, Maximum Weight: 2850kg
> 
> 0kg is meant for **body weight exercises!**
> **Note that exceeding these bounds will trigger an error!**

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Health: BMI

Calculates user's Body Mass Index (BMI) based on height and weight from user's input, and tracks it.

Format: `health /h:bmi /height:HEIGHT /weight:WEIGHT /date:DATE`

* `HEIGHT` is a **2 decimal point number in metres** (i.e. `1.71`) representing the user's height.
* `WEIGHT` is a **2 decimal point number in kilograms** (i.e. `60.50`) representing the user’s weight.
* `DATE` is in `DD-MM-YYYY` format (i.e. `19-03-2024`).

> ⚠️ Date specified cannot be later than the current date!

Examples:
* `health /h:bmi /height:1.70 /weight:75.42 /date:19-03-2024`
* `health /h:bmi /date:19-03-2024 /height:1.70 /weight:75.42`

PulsePilot will categorize your BMI as follows:

- BMI < 18.5 (less than 18.5): **Underweight**
- 18.5 <= BMI < 25.0 (more than or equal to 18.5 and less than 25.0): **Normal**
- 25.0 <= BMI < 30.0 (more than or equal to 25.0 and less than 30.0): **Overweight**
- 30.0 <= BMI < 40.0 (more than or equal to 30.0 and less than 40.0): **Obese**
- BMI >= 40.0 (more than 40.0): **Severely Obese**

Expected Output:

![Adding BMI](../img/output/adding_bmi.png)



> ⚠️ **Minimum and Maximum inputs:**
> Maximum Height: 2.75m, Minimum Height: 0.01m
> Maximum Weight: 640.00kg, Minimum Weight: 0.01kg
> 
> **Note that exceeding these bounds will trigger an error!**

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Health: Period

Tracks the start and end of user's menstrual cycle.

Format: `health /h:period /start:START_DATE [/end:END_DATE]`


* `START_DATE` is `DD-MM-YYYY` format (i.e. `19-03-2024`) representing the first day of period flow which is also the first day of the cycle. 

* `END_DATE` is `DD-MM-YYYY` format (i.e. `19-03-2024`) representing the last day of period flow. This parameter is **optional** and can be added once the period flow ends. To add an end date for a specific period, you need to input the correct corresponding start date.

> ⚠️ An outstanding period entry must have an end date specified before a new entry can be added.

Examples:

* `health /h:period /start:09-03-2022 /end:16-03-2022`
* `health /start:09-03-2022 /end:16-03-2022 /h:period`
* `health /h:period /start:09-03-2022`


Expected Output:

![Adding Periods](../img/output/adding_period.png)

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Health: Prediction

Predicts user's next period start date.

Format: `health /h:prediction`

* There must be at least **4 periods** added before a prediction can be made.

Expected Output:

![Viewing Prediction](../img/output/viewing_prediction.png)

> ⚠️ PulsePilot **does not** impose minimum or maximum length requirements for menstrual cycles, as underlying medical conditions can cause variations in cycle lengths.
> 
> PulsePilot will only **notify** you if your cycle length is beyond the healthy range of **2 - 7 days**.

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Health: Appointment

Tracks both **previous and upcoming** medical appointments.

Format: `health /h:appointment /date:DATE /time:TIME /description:DESCRIPTION`

* `DATE` is a `DD-MM-YYYY` format (i.e. `03-04-2024`) representing the date of the appointment.

* `TIME` is a `HH:mm` format (i.e. `14:15`) representing the time of the appointment.

* `DESCRIPTION` is a string (i.e. `review checkup with surgeon`) representing the details of the appointment. The description can **only contain alphanumeric characters, spaces, inverted commas and quotes**.

Examples:

* `health /h:appointment /date:03-04-2024 /time:14:15 /description:review checkup with surgeon`

* `health /date:03-04-2024 /description:review checkup with surgeon /time:14:15 /h:appointment`

Expected Output:

![Adding Appointment](../img/output/adding_appointment.png)

> ⚠️ Any characters that are **NOT** mentioned above used in the description will trigger an error! Please only use the characters allowed.

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### History

Prints all tracked instances of `run`, `gym`, `workouts`,  `bmi`, `period`, `appointment`.

Format: `history /item:TYPE`

* `TYPE` is either `run`, `gym`, `workouts`, `bmi`, `period`, `appointment`.
  - `run` shows all entries of runs.
  - `gym` shows all entries of gym.
  - `workouts` shows all entries of gym and runs.
  - `bmi` shows all BMI entries.
  - `period` shows all Period entries.
  - `appointment` show all Appointment entries.

> 💡 `workouts` prints a summary of the `run` and `gym` objects. Full details can be viewed using `history /item:run/gym` respectively.

Examples:
* `history /item:workouts`
* `history /item:appointment`

Expected Output:

![Viewing History](../img/output/viewing_history.png)

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Latest

Prints the **most recently added** instance of `run`, `gym`, `bmi`, `period`, `appointment`.

Format: `latest /item:TYPE`

* `TYPE` is either `run`, `gym`, `bmi`, `period` or `appointment`.
  - `run` shows the latest run
  - `gym` shows the latest gym
  - `bmi` shows the latest BMI by date
  - `period` shows the latest Period
  - `appointment` show the earliest upcoming Appointment

Examples:
* `latest /item:appointment`

Expected Output:

![Viewing Latest](../img/output/viewing_latest.png)

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Delete

Delete a tracked item.

Format: `delete /item:TYPE /index:INDEX`

* `TYPE` is either `run`, `gym`, `bmi`, `period` or `appointment`.
* `INDEX` represents the index of the item to delete.

> ⚠️ Please input positive integers for `INDEX` without leading zeros. Entering a number with a leading zero, such as `01`, will trigger an error.

> ⚠️ The `INDEX` is based on the respective item lists. Use `history` to view the lists.

Examples:

* `delete /item:run /index:2`

Expected output:

![Deleting Object](../img/output/deleting.png)

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Help

Prints the help message.

Format: `help`

Expected output:

![img.png](../img/output/viewing_help.png)

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

### Exit

Exits the bot **and writes to data file**.

Format: `exit`

Expected Output:

![Exiting Bot](../img/output/exit_bot.png)

> ⚠️ Exiting the bot by closing the terminal or with <kbd>Ctrl</kbd> + <kbd>C</kbd>  **will result in data being lost!**

###### [Back to experienced user manual](#experienced-user-manual)

###### [Back to table of contents](#table-of-contents)

---

## Command Summary

Here is a summary of all the commands and its functions. The table contains examples as well for you to try out!

| Action            | Format, Examples                                                                                                                                                          |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Print help        | `help`                                                                                                                                                                    |
| Add new run       | `workout /e:run /d:DISTANCE /t:TIME [/date:DATE]` <br> Example: `workout /e:run /d:5.24 /t:25:23 /date:19-03-2024`</br>                                                   |
| Add gym           | `workout /e:gym /n:NUMBER_OF_STATIONS [/date:DATE]` <br> Example: `workout /e:gym /n:4`</br>                                                                              |
| Track BMI         | `health /h:bmi /height:HEIGHT /weight:WEIGHT /date:DATE` <br> Example: `health /h:bmi /height:1.70 /weight:75.42 /date:19-03-2024`</br>                                   |
| Track Period      | `health /h:period /start:START_DATE [/end:END_DATE]` <br> Example: `health /h:period /start:09-03-2022 /end:16-03-2022`</br>                                              |
| Track Appointment | `health /h:appointment /date:DATE /time:TIME /description:DESCRIPTION` <br> Example: `health /h:appointment /date:29-04-2025 /time:12:00 /description:knee surgery` </br> |
| View history      | `history /item:TYPE` <br> Example: `history /item:run` </br>                                                                                                              |
| View latest       | `latest /item:TYPE` <br> Example: `latest /item:bmi` </br>                                                                                                                |
| Deleting item     | `delete /item:TYPE /index:INDEX` <br> Example: `delete /item:run /index:1`  </br>                                                                                         |
| Exit bot          | `exit`                                                                                                                                                                    |

###### [Back to table of contents](#table-of-contents)

---

## Common Problems

### Odd Characters on Screen

In some instances, the output from an error will result in odd characters being printed on screen:

![Colour not rendering](../img/output/colour_not_rendered.png)

This issue affects Windows machines. The odd characters are actually special characters used to **display colour** in the terminal. **Windows 10 users** do not have this enabled by default. For Windows 11, these are automatically enabled and hence this problem does not occur.

This is what the output is supposed to look like when the same command is used on a Windows 11 computer:

![Colour Rendered](../img/output/correct_colour_render.png)

This merely a visual difference, and it does not mean the bot is not working. **You can safely ignore this and continue using PulsePilot.**

> 💡 These 'special characters' are actually called [ANSI escape sequences](https://en.wikipedia.org/wiki/ANSI_escape_code). If you want to view PulsePilot in colour, please enable them for your Windows computer using [this guide](#https://www.youtube.com/watch?v=HeJOyEw3RtM). **MacOS and Linux users are unaffected!**

###### [Back to PulsePilot Text Style](#pulsepilot-text-style)

###### [Back to table of contents](#table-of-contents)

---

## Frequently Asked Questions

**1.** How do I transfer my data to another computer?

To transfer your data to another computer, make sure that `pulsepilot.jar` is placed in the **same folder** as `pulsepilot_data.txt` **and** `pulsepilot_hash.txt`. If done correctly, PulsePilot will recognize and synchronize your data.

> ⚠️ Create a _backup copy_ of both `pulsepilot_data.txt` and `pulsepilot_hash.txt` prior to file transfer to avoid data corruption.
>
> The _backup copies_ should be stored in a **separate** folder location from where the original `pulsepilot.jar` is saved.


**2.** What happens if my data is corrupted or tampered with?

> ❗ **_WARNING_: DO NOT** tamper with either `pulsepilot_data.txt` or `pulsepilot_hash.txt` to prevent **permanent** and **unrecoverable** loss of data.



You may experience 2 scenarios:

- A data file content corruption:

![Data Corruption](img/output/data_corruption.png)

Corruption of the `pulsepilot_data.txt` or `pulsepilot_hash.txt` files will result in **permanent and complete data loss**.

- A missing file error:

![Missing Files](img/output/missing_files.png)

A missing file error occurs when either `pulsepilot_data.txt` or `pulsepilot_hash.txt` is missing when PulsePilot is run. For safety and security reasons, PulsePilot will automatically delete any remaining data files before exiting the application.

**Both cases will inevitably result in permanent and complete data loss.**

> ❗ **DATA RECOVERY:** In both cases, you may want to recover data by utilising **both** your _backup_ copies of  `pulsepilot_data.txt` and `pulsepilot_hash.txt` to restore your data.

Otherwise, if you have lost your data, you can reinitialize a new save file by running the command `java -jar pulsepilot.jar` again.

**3.** Is my tracking data private and confidential?

Yes, your data is secure and stored locally on your machine. PulsePilot does not have any features that would allow it to send your data elsewhere.

**4.** What happens if I specify extra flags on accident?

Note that if you add duplicate or extra flags, the bot **will read the first instance only**.

**All other parameters will be ignored.**

For example:

```
workout /e:run /d:5.25 /t:59:50 /d:10.55
```

In the above output, the bot will read `5.25` as the distance. The second `/d:10.55` is ignored.

**5.** What if I keep receiving an error message even though my input seems to follow the instructions given in the user guide?

Please ensure that you follow the command syntax given **exactly** in the user guide. Some examples of mistakes that could be easily overlooked:

Example of the correct command:

![correct_command.png](img/correct_command.png)

- Error of adding extra space(s) in fixed parameters:
    - In this case, the altered fixed parameter is `/date:`, which was written as `/ date:` instead.

![extra_space_error_command.png](img/extra_space_error_command.png)

- Error of adding extra newline(s) after command:

![extra_newline_error_command.png](img/extra_newline_error_command.png)

Avoid using extra characters in the commands, such as blank space, newline, etc.

###### [Back to table of contents](#table-of-contents)

---

## Glossary

| Term                        | Definition                                                                                                                                                                                                                                                           |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Object-Oriented Programming | A programming paradigm aiming used to guide the the analysis and structure of solutions by programmers in a specific way. <br> [*Go Back*](#glossary-usage) </br>                                                                                                    |
| Hyperlinks                  | A reference to data that a user can follow by clicking on, which can point to an entire document or specific part of document. <br>[*Go Back*](#glossary-usage) </br>                                                                                                |
| Java                        | A programming language that was created to run programs **any operating system**. It was created based on the 'write once, run anywhere' philosophy. <br>[*Go Back*](#glossary-usage) </br>                                                                          |
| Command Line Interface      | A **text-based** interface where users can input commands that interact with a computer. <br>[*Go Back*](#command-line-interface) </br>                                                                                                                              |
| Directory / Directories     | A folder within your computer that contains other files and files.<br>[*Go Back*](#launching-cmdexe) </br>                                                                                                                                                           |
| Github                      | A platform that allows developers to create, store, manage , collaborate and share their code and applications. <br>[*Go Back*](#installing-and-launching-pulsepilot) </br>                                                                                          |
| Alphanumeric                | Input that is made up of only **letters and numbers**. <br>[*Go Back*](#creating-your-profile) </br>                                                                                                                                                                 |
| Flags                       | Flags in PulsePilot, like `/date:` or `/t:` are special signs used to tell it what information the user is giving. For example, the input `/date:20-04-2023` is used to tell PulsePilot that the date is 20 April 2023.  <br>[*Go Back*](#pulsepilot-commands) </br> |
| File Explorer               | An application used to view the files and directories in a Windows computer.<br> The program uses this: <img src=img_2101/windows/file_explorer.png alt="File Explorer" width="40"/> </br> <br> [*Go Back*](#windows-fix) </br>                                      |
| String                      | A sequence of characters that can be used to represent text data.                                                                                                                                                                                                    |

###### [Back to table of contents](#table-of-contents)

---
