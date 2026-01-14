# The Game – Basic File Analysis Lab

## Difficulty
Beginner

## Description
This lab focuses on *basic file analysis techniques* using a Linux environment to extract information from an unknown executable file.

## Scenario
An executable file named Tetris.exe was provided for analysis.  
The objective was to inspect the file and identify hidden or sensitive information using simple analysis techniques.

## Tools Used
- Kali Linux
- strings
- grep

## Methodology
1. The provided Tetris.exe file was extracted for analysis.
2. Initial inspection was performed using the strings command to identify readable text within the executable, since the file appeared to be obfuscated or encrypted.
3. The output from strings was then filtered using grep to search for patterns similar to a flag.
4. Through this process, the hidden flag was successfully identified.

## Key Learnings
- Importance of initial static analysis when dealing with unknown executables
- How the strings command can reveal valuable information
- Using grep to efficiently filter and locate relevant data
- Basic investigative workflow from a Blue Team perspective

## Conclusion
This lab demonstrates how simple tools and techniques can be effective during the early stages of file analysis, reinforcing fundamental Blue Team concepts.


## Notes
All analysis was performed in a controlled and authorized lab environment for educational purposes.
