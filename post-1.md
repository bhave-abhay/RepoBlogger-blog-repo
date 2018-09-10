## You can learn programming using ONLY a web browser

Yes, you read it correct! :eyes: <br />
Programming is not rocket science.
Let's get to the very basics. In Layman's terms. No fuss.

Programming is actually much simpler than many of us might think. We always have a lot of programmable things around us. We _can_ program them to do wonderful things for us. It's only a question of a few things:-

1. You need to know what you want the program to do. You need to know what it's function is, what it's **_logic_** is.
1. You need to know what **_technology_** is needed
1. You need to install a few **_dev-tools_** on your computer accordingly
1. You need to write **_source code_** for what you want your program to do
1. You need to **_build_** and **_deploy_** your program so that people can **_run_** it

#### 1. Building logic
If you are not sure where you are going, you don't start your car, do you? As obvious, you need to know what your program will do. The clearer the idea you have about it, the better.
#### 2. Choosing technology
Technology choice is mostly governed by _where_ and _how_ you want to use the program. If you want to build a robotic car, Arduino and C/CPP will be nice choices, because arduino is small, and can do the things needed for the car to do. If you want to build a billing software for a small garment retailer, you might choose VB.Net and MSSqlExpress because that retailer is going to use it on their windows PC.

What you want to create decides how it _may_ be good to do. It's not the restricting factor.

Some branches of programming technology have evolved in a specialized domain. The developer community has developed a robust pool of libraries for doing some domain specific things, so you can make use of it and speed up your development process. If you choose a technology that is not a common choice for developing programs of similar purpose or similar processing, you  might have to do more things yourself as there might not be libraries available to you for doing those things.

#### 3. Development Environment Set-up
According to the technologies chosen, you need to install developer tools and set up your machine. Basically it will involve
1. Installing development tools for that platform.
   - GCC and MAKE for C / C++
   - JDK for Java
   - Android SDK for Android Apps
   - XCode for iOS and Mac OS-X apps
   - etc.
1. Setting up your machine
   - Configuration of paths
   - Configuration of individual tools
   - etc.

We will not go into it's details right now. As and when needed, we will cover the detailed process of installing and configuring various developer toolchains for different technologies. But at the end of this step, your machine is capable of _building_ a project that results into a usable software for the chosen platform or technology

#### 4. Development

You split the program's task in smaller and smaller parts. And then you specify it in form of _source code_ written in some **_programming language_**. The machines do not readily understand these _english-like_ programming languages. That's why you need the _dev-tools_. They will eventually translate your source code into some _executable_ thing.

You need not re-invent the wheel every day. There are lot of libraries which can assist your program in doing what you want it to do. So, your source code can make use of them instead of you specifying every damn thing. Reading a file from hard disk has a LOT of things involved - Hard disk type (magnetic / ssd / tape drive / ...), File system (FAT, NTFS, EXF, ...), ... Your source will not handle all these details itself. It will rely on some library for handling files. That library will rely on the Hard Disk Driver program sitting on the system and delegeting the disk operations for all the programs. This way, your source code can specifiy only the operations to be done specific to your special purpose. This reduces the amount of work needed for development process.

Once you completely and neatly figure out what you want your program to do, it's quiet simple to write that into some _programming language_. In fact, for the same task, if we right code in 10 or 50 different programming languages, it won't look tremendously different from each other. Because it's the same task, after all!

It's the process of specifying the _task_ you want the computer do, to the computer, in a way it can understand.
One obvious prerequisite of it is, that you already understand the task!

If the overall function of your software is vast, you have to divide it into smaller components. Each component should now be designed in such a way that they all fit together and work together consistantly. This is the _art_ known as **"Software Architecture"**.

#### 5. Deployment

Your source code is of no direct use. It needs to _Run_. And for that, the machine needs to understand it.

Enter the dev-tools. They are the programs that translate your programs into executable form. Machines understand those executables, so now you can _run_ the program.

For simple programs, it's just a single step. For large software, you may have to perform a bunch of things. In that case, it's not a great idea to rely on your own memory for remembering all the steps in details. With a neat dev tool chain, you can _script_ your build and deployment process, so that you can run those scripts as per need. You can _chain_ the steps together in a way that's needed for your project. This comparitively ignored but a fantastic and essential  craft is called **Build Engineering**, and is very, very important factor for managing the deployment of large, and especially multi-platform projects.
##### Bingo!
Your program's now deployed. You can run the program so that it can do the task you specified.<br />
Feel proud! You just made your machine a bit (pardon the pun) smarter!
