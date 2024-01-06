# Linux Shell Wrapper Software

the shell supports:
* namely all shell command (e.g., ls , pwd).
* the __&__ operator for background execution.
* the "exit" command to exit the shell.
* a log file.

----
Please find:
- more on the problem statement in __Problem_Statment.pdf__.
- more on the solution and design in __Docs.pdf__.
- the code and how to execute it in __code__ folder.
- the demo short video [here](https://youtu.be/zDjLADJGXFs).

  
##Docs.pdf  Table of Contents
1. [Problem Statement](#problem-statement)
2. [Software Design and Block Diagram](#software-design-and-block-diagram)
   - 2.1 [Pipeline Command Treatment](#pipeline-command-treatment)
      - 2.1.1 [Stage: Get Command](#stage-get-command)
      - 2.1.2 [Stage: Convert Command](#stage-convert-command)
      - 2.1.3 [Stage: Execute Commands](#stage-execute-commands)
   - 2.2 [Super Loop Architecture](#super-loop-architecture)
3. [Sample Runs](#sample-runs)
   - 3.1 [Minimal Foreground Command](#minimal-foreground-command)
   - 3.2 [Empty and “Exit” Commands](#empty-and-exit-commands)
   - 3.3 [Commands with “&”](#commands-with-)
4. [Appendix](#appendix)
   - 4.1 [Source Code](#source-code)
   - 4.2 [Screenshot of Processes](#screenshot-of-processes)
