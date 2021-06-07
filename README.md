# Hi there, my name is Sam Belliveau

## Robotics

I was the President of Software Engineering for the Stuyvesant Robotics Team. Examples of my work can be seen in projects such as [StuyLib](https://github.com/StuyPulse/StuyLib), or [Edwin](https://github.com/StuyPulse/Edwin). I am the inital creator of StuyLib and have contributed the vast majority of the code and documentation. For Edwin I am resposible for restructuring all of the robot code, and cleaning up the subsystems to perform correctly. Much of my other work for the robotics team has been with regards to research, which is not visible on github.

## Personal Projects

A lot of my work has gone into libraries or random utilities for C++, many of which are on [my gist](https://gist.github.com/Sam-Belliveau). I have extensive experience with esoteric aspects of C++ such as SFINAE or template meta-programming. 

I like to make my projects very low level, and I don't make many webapps, or user interfaces at all for that matter. Most of my code would be what you would consider backend code, or even library code for some of my C++ projects. So if you would like to test out many of my projects you may need to know a decent amount of C++ to begin with.

### Some of My Favorite Projects:

= [Sams-Marcher](https://github.com/Sam-Belliveau/Sams-Marcher): a very simple ray marcher that I built from the ground up to test out some cool math.
- [Upside Down](https://github.com/Sam-Belliveau/Upside-Down): a game written from the ground up in C++ with a fully working level editor, game mechanics, and it is structured in a way that makes it really easy to add new content.
- [Infix Notation Evaluator](https://gist.github.com/Sam-Belliveau/3c90f0f05368f0e5dbb0c9a0b37e1025): very simple, but blazing fast infix notation evaluator. It takes in a math problem as a string and evaluates it extremely quickly. While it is not turing complete, it is fast enough to use in something such as a graphing calculator. 
- [CRC Hashing C++](https://gist.github.com/Sam-Belliveau/72ba4a8710324ce7a1ac1789d64ec831): very fast / optimized implementation of CRC in C++ using template programming and SFINAE. Because of the heavy use of SFINAE _(concepts were not a thing yet)_, it is able to recursively hash almost every type that can be broken down into integers. It can iterate across lists, strings, and even lists of lists to give you a cyclic redundancy check of any data type. It can do all of that, at compile time, making it blazing fast.
- [Markov Chain in Rust](https://github.com/Sam-Belliveau/Markov-Chain): this is a very simple yet very fast text generator app programmed in rust. Given a large amount of text, this app is able to build a probablity set, and then using that probablity set, it is able to very rapidly generate new text. It is often fun to use this program to imitate somebody's writing style, as it generates gibberish that is eerily similar to human speach.
- [TheSamBoy, GameBoy Emulator](https://github.com/Sam-Belliveau/TheSamBoy): this was one of my most ambitious projects, which was a GameBoy emulator written in rust. It currently does not boot any games as the interrupt timings of the CPU were too difficult for me to get down based off of the CPU documentation alone. I may revisit this project if I learn more about the inner workings of a computer, however this emulator is still able to simulate most of the ISA for the Z80 CPU.
- [SPGL](https://github.com/Sam-Belliveau/SPGL): this project is a very simple framebuffer emulator that allows you to quickly draw pixels to the screen using SDL. I had a lot of fun writing this and even made a few demos with it, but it was relatively limited in the end.
- [C++ Meta Programming](https://github.com/Sam-Belliveau/CPP-Meta-Programing): this project was more of a test than anything, which proved that C++ Meta Programming is infact turing complete. It is a lot of fun to write programs in this manner, but it is pretty useless now that constexpr is a thing.
- [NetLogo Ray Tracer](https://gist.github.com/Sam-Belliveau/f266a54d3523843563b2b172dee71b53): an overkill Intro2CS final project I made in NetLogo. It is a working, yet limited, raytracer that operates within the bounds of netlogo without any extensions. Many of the limitations, such as with the shapes that are permitted, are made in order to keep the speed and graphics reasonable. I am very proud with how this turned out.
- [SDISC](https://github.com/Sam-Belliveau/SDISC): a very simple proof of concept CPU design I made in the 8th grade. It is not realistic, and the ISA is made up of 16 instructions in total. It is turing complete, but would be tremendously difficult to do anything usefull due to the lack of comfort features, such as a stack.

## Github Stats

[![Sam Belliveau's Github Stats](https://github-readme-stats.vercel.app/api?username=Sam-Belliveau&count_private=true)](https://github.com/Sam-Belliveau)
