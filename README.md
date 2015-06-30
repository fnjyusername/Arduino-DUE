# Arduino-DUE

SPECS: AT91SAM3X8E ATMEL CHIPSET, 32bit, 84Mhz

## TIMER BLOCK
The AT91SAM3X8E has nine (9) general-purpose 32-bit timers/counters organized in three blocks i.e. TC0, TC1, TC3.
Each Block has 3 channels i.e. 0, 1, 2 and each channel of each block has input and output lines.

*TABLE 1
Instance | TC  | Channel| External Clock Input | I/O Line A | I/O Line B
---------|-----|--------|----------------------|------------|-----------
 T0      | TC0 |   0    |         TCLK0        |   TIOA0    |    TIOB0
 T1      | TC0 |   1    |         TCLK1        |   TIOA1    |    TIOB1
 T2      | TC0 |   2    |         TCLK2        |   TIOA2    |    TIOB2
 T3      | TC1 |   0    |         TCLK3        |   TIOA3    |    TIOB3
 T4      | TC1 |   1    |         TCLK4        |   TIOA4    |    TIOB4
 T5      | TC1 |   2    |         TCLK5        |   TIOA5    |    TIOB5
 T6      | TC2 |   0    |         TCLK6        |   TIOA6    |    TIOB6
 T7      | TC2 |   1    |         TCLK7        |   TIOA7    |    TIOB7
 T8      | TC2 |   2    |         TCLK8        |   TIOA8    |    TIOB8






