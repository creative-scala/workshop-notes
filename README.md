# Notes on using Creative Scala

If you're running a ScalaBridge or other session using Creative Scala these notes may be useful to you.


## Creative Scala Website

Creative Scala is online at http://www.creativescala.org/  That's the easiest way for participants to get hold of the source. I've not widely disseminated this website due to _stupid reasons_.


## Installation

Creative Scala has installation instructions for two toolchains: an editor and the terminal, or IntelliJ. I have a weak preference for the editor+terminal route. I prefer this route as it's simpler to setup, and IntelliJ can report errors (red squiggly lines) that don't indicate real problems. My preference is weak because I don't have much experience with IntelliJ. 

For some reason people skim through the installation instructions and choose IntelliJ, which comes second in that chapter.


## Workflow 

Finding an efficient workflow is important. In Creative Scala students are likely to run code much more frequently, and make much smaller changes, than is typical in most development workflows. I find the fastest workflow to use the `:paste` command in the Scala console. A lot of people don't know about this so here's a quick rundown of how to use it:

- start the console, or REPL, from within SBT using the `console` command
- use the `:paste` command to load the file of interest. In the template project this is `Example.scala`. The command is `:paste src/main/scala/Example.scala`. Note that tab completion works! You don't have to type this all out!
- after making a change `:paste` the file again. Note you can just press the up arrow to access previous commands in the console. No need to type it out again!

I find this workflow very effective for quickly iterating on code. There is one downside: you cannot declare a `package` for any code you `:paste`. This shouldn't be a problem for Creative Scala uses.


## Pathways

People will come to Creative Scala with different backgrounds. Some will love creating pictures, and some will just want to get through the code as quickly as possible. Some will already be proficient programmers, and some will have never programmed before. Creative Scala aims to provide something of interest to everyone, but not everyone will be interested in everything and that is fine.

In particular people should feel free to skim parts they aren't interested in. For example, some parts of Creative Scala ask participants to do some trigonometry. If they struggle with this or aren't interested in it, it's fine to skip this. All the exercises have solutions, and in some cases the solutions have extensive commentary. Read the answers and then move on!


## Key Points

The key points of Creative Scala are the substitution model of evaluation, and structural recursion. These concepts are big and powerful. It's worth spending some time on these. Experienced programmers, coming from imperative languages, will probably skim these but slowing down here will be helpful for them as this will help with the mental shift that FP requires.


## Groups

Organising people into groups of similar experience is useful. Collaboration is useful. It's not an exam. You're allowed---even encouraged!---to talk.
