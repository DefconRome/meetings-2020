## Breaking apps from the inside: an introduction to the FRIDA binary instrumentation framework, by Radamanth

In this talk, we'll be giving a introductory look at FRIDA, a binary instrumentation toolkit.

Reverse engineering and researching applications is hard, especially when trying to understand dynamic behaviours. FRIDA allows you to explore that space, by offering a rich API for interfacing with running binaries, debugging, intercepting (and modifying) functions and syscalls, all in the comfort of Javascript!

We'll be also displaying some demos of the functionality of FRIDA's API, along some extra tooling that will make the process of injecting our library and analyzing the behaviour easier

## Breaking the walls: CPU introspection through micro-architectural data sampling, by pietroborrello

While the x86 instruction set architecture strictly defines the observable behavior of modern CPU, its inner workings remains highly undocumented. The micro-operations that govern the processor are hidden behind a wall. 
Let's break this wall using vulnerabilities of the CPU itself, to build a sniffer that precisely observes the micro-architectural activity.
Have you ever wanted to see how does a Spectre attack looks like from *inside* the CPU? Come and see, we don't like walls!
This talk is based on the recent work of Brandon Falk.
