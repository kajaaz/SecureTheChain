### What value should be sent to the code so that it do not revert ?

***************************************

00	34	CALLVALUE
01	56	JUMP
02	FD	REVERT 
03	FD	REVERT
04      FD      REVERT
05      FD      REVERT
06      FD      REVERT
07      FD      REVERT
08	5B	JUMPDEST
09	00	STOP

? Enter the value to send to the code :

***************************************

Help : https://www.evm.codes/precompiled
Source : EVM Puzzle
