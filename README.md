# MinimalSizeExecutables
Various examples demonstrating practical means for how to reduce executable footprint size (with various trade-offs).
I'm not so much focused on the smallest possible executable size (for which many great examples can be found) but more about sensible reductions, and their trade-offs, without having to completely change the programming approach used. For example: I could re-write almost any C/C++ program in assembly (assuming I can do better than the compiler, which is very debatable in my case!).

# Why? Just... why?
I don't really have a great explanation here, but I just have always found it interesting to see "how low can you go?". Maybe it comes from starting coding life on a Commodore 64 writing in a machine code monitor, or perhaps it's a psychological need to control everything.

# Initial Focus
I'll start with a Windows GUI application and a Windows console application, built for both x86 and x64, using the most modern toolchain which will be Visual Studio 2019, but targetting the oldest supported version of Windows I can get away with (Windows XP). I'll start using Microsoft Visual C++, but may then venture in to using the version of Clang which ships with it.

# What else?
I may go back through the history of Visual Studio versions seeing what differs in terms of minimal footprint size, because some "features" of the compiler/linker either cannot be disabled/excluded, but it's also interesting (to me at least) to see what has changed over time.

# Related work
