_________________________________________________________________________________________________________
CONCLUSION
_________________________________________________________________________________________________________
Your system appears to be suitable for handling real-time audio and other tasks without dropouts. 
LatencyMon has been analyzing your system for  0:01:00  (h:mm:ss) on all processors.


_________________________________________________________________________________________________________
SYSTEM INFORMATION
_________________________________________________________________________________________________________
Computer name:                                        DESKTOP-7N3GI76
OS version:                                           Windows 10, 10.0, version 1803, build: 17134 (x64)
Hardware:                                             
CPU:                                                  GenuineIntel Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz
Logical processors:                                   4
Processor groups:                                     1
RAM:                                                  4095 MB total


_________________________________________________________________________________________________________
CPU SPEED
_________________________________________________________________________________________________________
Reported CPU speed:                                   3696 MHz

Note: reported execution times may be calculated based on a fixed reported CPU speed. Disable variable speed settings like Intel Speed Step and AMD Cool N Quiet in the BIOS setup for more accurate results.


_________________________________________________________________________________________________________
MEASURED INTERRUPT TO USER PROCESS LATENCIES
_________________________________________________________________________________________________________
The interrupt to process latency reflects the measured interval that a usermode process needed to respond to a hardware request from the moment the interrupt service routine started execution. This includes the scheduling and execution of a DPC routine, the signaling of an event and the waking up of a usermode thread from an idle wait state in response to that event.

Highest measured interrupt to process latency (탎):   70,80
Average measured interrupt to process latency (탎):   6,420576

Highest measured interrupt to DPC latency (탎):       65,70
Average measured interrupt to DPC latency (탎):       3,348713


_________________________________________________________________________________________________________
 REPORTED ISRs
_________________________________________________________________________________________________________
Interrupt service routines are routines installed by the OS and device drivers that execute in response to a hardware interrupt signal.

Highest ISR routine execution time (탎):              320,996212
Driver with highest ISR routine execution time:       storport.sys - Microsoft Storage Port Driver, Microsoft Corporation

Highest reported total ISR routine time (%):          0,003403
Driver with highest ISR total time:                   storport.sys - Microsoft Storage Port Driver, Microsoft Corporation

Total time spent in ISRs (%)                          0,003887

ISR count (execution time <250 탎):                   563
ISR count (execution time 250-500 탎):                0
ISR count (execution time 500-1000 탎):               5
ISR count (execution time 1000-2000 탎):              0
ISR count (execution time 2000-4000 탎):              0
ISR count (execution time >=4000 탎):                 0


_________________________________________________________________________________________________________
REPORTED DPCs
_________________________________________________________________________________________________________
DPC routines are part of the interrupt servicing dispatch mechanism and disable the possibility for a process to utilize the CPU while it is interrupted until the DPC has finished execution.

Highest DPC routine execution time (탎):              128,007035
Driver with highest DPC routine execution time:       ntoskrnl.exe - NT Kernel & System, Microsoft Corporation

Highest reported total DPC routine time (%):          0,133952
Driver with highest DPC total execution time:         rspLLL64.sys - Resplendence Latency Monitoring and Auxiliary Kernel Library, Resplendence Software Projects Sp.

Total time spent in DPCs (%)                          0,136599

DPC count (execution time <250 탎):                   197517
DPC count (execution time 250-500 탎):                0
DPC count (execution time 500-10000 탎):              0
DPC count (execution time 1000-2000 탎):              0
DPC count (execution time 2000-4000 탎):              0
DPC count (execution time >=4000 탎):                 0


_________________________________________________________________________________________________________
 REPORTED HARD PAGEFAULTS
_________________________________________________________________________________________________________
Hard pagefaults are events that get triggered by making use of virtual memory that is not resident in RAM but backed by a memory mapped file on disk. The process of resolving the hard pagefault requires reading in the memory from disk while the process is interrupted and blocked from execution.

NOTE: some processes were hit by hard pagefaults. If these were programs producing audio, they are likely to interrupt the audio stream resulting in dropouts, clicks and pops. Check the Processes tab to see which programs were hit.

Process with highest pagefault count:                 wmiprvse.exe

Total number of hard pagefaults                       82
Hard pagefault count of hardest hit process:          27
Number of processes hit:                              6


_________________________________________________________________________________________________________
 PER CPU DATA
_________________________________________________________________________________________________________
CPU 0 Interrupt cycle time (s):                       1,617693
CPU 0 ISR highest execution time (탎):                16,577381
CPU 0 ISR total execution time (s):                   0,000075
CPU 0 ISR count:                                      7
CPU 0 DPC highest execution time (탎):                128,007035
CPU 0 DPC total execution time (s):                   0,324873
CPU 0 DPC count:                                      196811
_________________________________________________________________________________________________________
CPU 1 Interrupt cycle time (s):                       1,214845
CPU 1 ISR highest execution time (탎):                21,842532
CPU 1 ISR total execution time (s):                   0,000032
CPU 1 ISR count:                                      2
CPU 1 DPC highest execution time (탎):                59,524351
CPU 1 DPC total execution time (s):                   0,000422
CPU 1 DPC count:                                      96
_________________________________________________________________________________________________________
CPU 2 Interrupt cycle time (s):                       0,873391
CPU 2 ISR highest execution time (탎):                44,132035
CPU 2 ISR total execution time (s):                   0,000254
CPU 2 ISR count:                                      16
CPU 2 DPC highest execution time (탎):                16,569805
CPU 2 DPC total execution time (s):                   0,000966
CPU 2 DPC count:                                      232
_________________________________________________________________________________________________________
CPU 3 Interrupt cycle time (s):                       0,781681
CPU 3 ISR highest execution time (탎):                320,996212
CPU 3 ISR total execution time (s):                   0,008975
CPU 3 ISR count:                                      543
CPU 3 DPC highest execution time (탎):                17,421537
CPU 3 DPC total execution time (s):                   0,001834
CPU 3 DPC count:                                      378
_________________________________________________________________________________________________________
