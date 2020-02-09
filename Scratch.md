## Bugs

- Getting the frog and bear to switch at the same time.
  - Fix: Add 3 specific distinct script start and end commands with user key board commands.
- Frog croak kept going on after it was suppose to.
  - Fix: Stop all voice is applied after vocal loop is suppose to be done. And another stop all voice at the beginning of following script.
- Speech bubbles not fully going through loop as well as scripts ending early.
  - Fix: 30 second wait timer was added to the end of every script. This significantly improved the success of the scripts working bug free until the script was suppose to end and a new script picked up.

## Code copied

- Used: (say[join{answer}])
  - Source: R.D.W. Rome git hub > LMSC261-SP20 > Lesson-02C > ScratchSamples > 2.Variables.sb3
