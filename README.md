Hello,

This is a repo of examples on how to render graphics using the win32 GDI api and the Odin language.

All examples (unless specifically specified in the file) can be built and run using:

odin run .

Please keep in mind this repository was being used as a learning dump for me to put finished examples in; meaning things I was learning
are then placed in this repo not the actual learning process.

It is not meant to be a tutorial repository, but can be if you're willing to put in the work to study the code and take notes.
This code is not guarenteed to be the best or most performant approach for these tasks. That is by design; I am trying to figure how how GDI works,

The goal was to originally make a game with GDI but I have since decided against doing that as I want to move on to trying other things with Odin.

The main resource used for figuring out how GDI works are:
- the win32 API official documentation: https://learn.microsoft.com/en-us/windows/win32/
- Odin language windows source code
- AI Tools

Win32 API Official Documentation is really the best place to check for argument explinations. A more simplier explination can be found with AI Tools.
The Odin bindings for win32 really show how it's implimented in Odin. I recommend just copying the procedure and just slotting in what's needed.
You will see almost all procedures in this code use named arguments, that is why. I just copy/paste, slot in where and what needed

For studying C examples; I use AI tools like Copilot and PHIND. I find the odin generation from AI Tools to be incorrect at best and syntatically wrong most of the time.
So I have them generate C examples and translate that into Odin myself -- suprisingly easy and worth the effort for learning.
