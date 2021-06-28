_________________________________________________________________________________________________________
CONCLUSION
_________________________________________________________________________________________________________
Your system appears to be suitable for handling real-time audio and other tasks without dropouts. 
LatencyMon has been analyzing your system for  0:01:00  (h:mm:ss) on all processors.


_________________________________________________________________________________________________________
SYSTEM INFORMATION
_________________________________________________________________________________________________________
Computer name:                                        DESKTOP-6JV81BF
OS version:                                           Windows 10, 10.0, version 1709, build: 16299 (x64)
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

Highest measured interrupt to process latency (µs):   321,108136
Average measured interrupt to process latency (µs):   6,424480

Highest measured interrupt to DPC latency (µs):       317,783462
Average measured interrupt to DPC latency (µs):       3,302459


_________________________________________________________________________________________________________
 REPORTED ISRs
_________________________________________________________________________________________________________
Interrupt service routines are routines installed by the OS and device drivers that execute in response to a hardware interrupt signal.

Highest ISR routine execution time (µs):              321,814935
Driver with highest ISR routine execution time:       storport.sys - Microsoft Storage Port Driver, Microsoft Corporation

Highest reported total ISR routine time (%):          0,001865
Driver with highest ISR total time:                   storport.sys - Microsoft Storage Port Driver, Microsoft Corporation

Total time spent in ISRs (%)                          0,002661

ISR count (execution time <250 µs):                   396
ISR count (execution time 250-500 µs):                0
ISR count (execution time 500-1000 µs):               3
ISR count (execution time 1000-2000 µs):              0
ISR count (execution time 2000-4000 µs):              0
ISR count (execution time >=4000 µs):                 0


_________________________________________________________________________________________________________
REPORTED DPCs
_________________________________________________________________________________________________________
DPC routines are part of the interrupt servicing dispatch mechanism and disable the possibility for a process to utilize the CPU while it is interrupted until the DPC has finished execution.

Highest DPC routine execution time (µs):              84,422619
Driver with highest DPC routine execution time:       VBoxGuest.sys - VirtualBox Guest Driver, Oracle Corporation

Highest reported total DPC routine time (%):          0,135814
Driver with highest DPC total execution time:         rspLLL64.sys - Resplendence Latency Monitoring and Auxiliary Kernel Library, Resplendence Software Projects Sp.

Total time spent in DPCs (%)                          0,138219

DPC count (execution time <250 µs):                   199444
DPC count (execution time 250-500 µs):                0
DPC count (execution time 500-10000 µs):              0
DPC count (execution time 1000-2000 µs):              0
DPC count (execution time 2000-4000 µs):              0
DPC count (execution time >=4000 µs):                 0


_________________________________________________________________________________________________________
 REPORTED HARD PAGEFAULTS
_________________________________________________________________________________________________________
Hard pagefaults are events that get triggered by making use of virtual memory that is not resident in RAM but backed by a memory mapped file on disk. The process of resolving the hard pagefault requires reading in the memory from disk while the process is interrupted and blocked from execution.

NOTE: some processes were hit by hard pagefaults. If these were programs producing audio, they are likely to interrupt the audio stream resulting in dropouts, clicks and pops. Check the Processes tab to see which programs were hit.

Process with highest pagefault count:                 sppsvc.exe

Total number of hard pagefaults                       9
Hard pagefault count of hardest hit process:          6
Number of processes hit:                              3


_________________________________________________________________________________________________________
 PER CPU DATA
_________________________________________________________________________________________________________
CPU 0 Interrupt cycle time (s):                       1,617179
CPU 0 ISR highest execution time (µs):                309,020022
CPU 0 ISR total execution time (s):                   0,000336
CPU 0 ISR count:                                      3
CPU 0 DPC highest execution time (µs):                28,489177
CPU 0 DPC total execution time (s):                   0,328974
CPU 0 DPC count:                                      198997
_________________________________________________________________________________________________________
CPU 1 Interrupt cycle time (s):                       1,281401
CPU 1 ISR highest execution time (µs):                0,0
CPU 1 ISR total execution time (s):                   0,0
CPU 1 ISR count:                                      0
CPU 1 DPC highest execution time (µs):                10,277597
CPU 1 DPC total execution time (s):                   0,000015
CPU 1 DPC count:                                      4
_________________________________________________________________________________________________________
CPU 2 Interrupt cycle time (s):                       0,893415
CPU 2 ISR highest execution time (µs):                17,270563
CPU 2 ISR total execution time (s):                   0,000081
CPU 2 ISR count:                                      5
CPU 2 DPC highest execution time (µs):                19,177489
CPU 2 DPC total execution time (s):                   0,000886
CPU 2 DPC count:                                      174
_________________________________________________________________________________________________________
CPU 3 Interrupt cycle time (s):                       0,633430
CPU 3 ISR highest execution time (µs):                321,814935
CPU 3 ISR total execution time (s):                   0,005972
CPU 3 ISR count:                                      391
CPU 3 DPC highest execution time (µs):                84,422619
CPU 3 DPC total execution time (s):                   0,001940
CPU 3 DPC count:                                      269
_________________________________________________________________________________________________________
