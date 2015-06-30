# Arduino-DUE

SPECS: AT91SAM3X8E ATMEL CHIPSET, 32bit, 84Mhz

## TIMER BLOCK
The AT91SAM3X8E has nine (9) general-purpose 32-bit timers/counters i.e. TCLK0, TCLK1, TCLK2, ...TCLK8. These timers/counter is organized in three blocks i.e. TC0, TC1, TC3. Each Block has 3 channels i.e. 0, 1, 2 and each channel of each block has two (2) input and output lines labelled as line A and B.

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



Clock Input  |    Port Pin      |      Pin on
 (TCLKx)     |      Chip        | Arduino Due Board
-------------|------------------|-----------------------
 TCLK0       |    PB 26         |   Pin 22 (Digital)
 TCLK1       |    PA  4         |   Pin  5 (Analog In)
 TCLK2       |    PA  7         |   Pin 31 (Digital )
 TCLK3       |    PA 22         |   Pin  5 (Analog In)
 TCLK4       |    PA 23         |   Pin  2 (Analog In)
 TCLK5       |    PB 16         |   DAC1
 TCLK6       |    PC 27         |        /
 TCLK7       |    PC 30         |   LED "RX"
 TCLK8       |    PD  9         |   Pin 30 (Digital)





