_________________________________________________________________________________________________________
CONCLUSION
_________________________________________________________________________________________________________
Your system appears to be suitable for handling real-time audio and other tasks without dropouts. 
LatencyMon has been analyzing your system for  0:01:00  (h:mm:ss) on all processors.


_________________________________________________________________________________________________________
SYSTEM INFORMATION
_________________________________________________________________________________________________________
Computer name:                                        DESKTOP-2EFC3KB
OS version:                                           Windows 10, 10.0, version 2009, build: 19043 (x64)
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

Highest measured interrupt to process latency (µs):   321,10
Average measured interrupt to process latency (µs):   6,802565

Highest measured interrupt to DPC latency (µs):       313,40
Average measured interrupt to DPC latency (µs):       3,132143


_________________________________________________________________________________________________________
 REPORTED ISRs
_________________________________________________________________________________________________________
Interrupt service routines are routines installed by the OS and device drivers that execute in response to a hardware interrupt signal.

Highest ISR routine execution time (µs):              396,654762
Driver with highest ISR routine execution time:       storport.sys - Microsoft Storage Port Driver, Microsoft Corporation

Highest reported total ISR routine time (%):          0,029965
Driver with highest ISR total time:                   storport.sys - Microsoft Storage Port Driver, Microsoft Corporation

Total time spent in ISRs (%)                          0,030592

ISR count (execution time <250 µs):                   5326
ISR count (execution time 250-500 µs):                0
ISR count (execution time 500-1000 µs):               7
ISR count (execution time 1000-2000 µs):              0
ISR count (execution time 2000-4000 µs):              0
ISR count (execution time >=4000 µs):                 0


_________________________________________________________________________________________________________
REPORTED DPCs
_________________________________________________________________________________________________________
DPC routines are part of the interrupt servicing dispatch mechanism and disable the possibility for a process to utilize the CPU while it is interrupted until the DPC has finished execution.

Highest DPC routine execution time (µs):              63,694805
Driver with highest DPC routine execution time:       storport.sys - Microsoft Storage Port Driver, Microsoft Corporation

Highest reported total DPC routine time (%):          0,009695
Driver with highest DPC total execution time:         rspLLL64.sys - Resplendence Latency Monitoring and Auxiliary Kernel Library, Resplendence Software Projects Sp.

Total time spent in DPCs (%)                          0,019358

DPC count (execution time <250 µs):                   21517
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

Process with highest pagefault count:                 svchost.exe

Total number of hard pagefaults                       1987
Hard pagefault count of hardest hit process:          1857
Number of processes hit:                              5


_________________________________________________________________________________________________________
 PER CPU DATA
_________________________________________________________________________________________________________
CPU 0 Interrupt cycle time (s):                       2,867712
CPU 0 ISR highest execution time (µs):                307,009740
CPU 0 ISR total execution time (s):                   0,000307
CPU 0 ISR count:                                      1
CPU 0 DPC highest execution time (µs):                55,600108
CPU 0 DPC total execution time (s):                   0,025590
CPU 0 DPC count:                                      15471
_________________________________________________________________________________________________________
CPU 1 Interrupt cycle time (s):                       0,260396
CPU 1 ISR highest execution time (µs):                344,751623
CPU 1 ISR total execution time (s):                   0,000745
CPU 1 ISR count:                                      6
CPU 1 DPC highest execution time (µs):                63,694805
CPU 1 DPC total execution time (s):                   0,012511
CPU 1 DPC count:                                      3109
_________________________________________________________________________________________________________
CPU 2 Interrupt cycle time (s):                       0,230050
CPU 2 ISR highest execution time (µs):                17,178030
CPU 2 ISR total execution time (s):                   0,000346
CPU 2 ISR count:                                      26
CPU 2 DPC highest execution time (µs):                13,219697
CPU 2 DPC total execution time (s):                   0,001399
CPU 2 DPC count:                                      416
_________________________________________________________________________________________________________
CPU 3 Interrupt cycle time (s):                       0,337116
CPU 3 ISR highest execution time (µs):                396,654762
CPU 3 ISR total execution time (s):                   0,072942
CPU 3 ISR count:                                      5300
CPU 3 DPC highest execution time (µs):                19,469156
CPU 3 DPC total execution time (s):                   0,007539
CPU 3 DPC count:                                      2521
_________________________________________________________________________________________________________
