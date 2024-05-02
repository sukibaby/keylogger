# CSV Keylogger

This was made to use in conjuction with https://github.com/sukibaby/stepmania-sync-tester to both verify the timing of the Pico and provide a set of timestamps showing when the system receives an input to compare against when the game engine reports it received an input.

All code relevant to hiding the keylogger or any sneaky stuff like that was 100% removed so that there is no chance it can be run without somebody's knowledge.

The keylogger produces a CSV file with an output like this:

```
1714713795969,h
1714713796225,e
1714713796433,l
1714713796641,l
1714713796929,o
1714713797249,[SPACE]
1714713797489,g
1714713797681,i
1714713797777,t
1714713798025,h
1714713798209,u
1714713798329,b
1714713798953,!
```
