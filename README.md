# Pico PIO ISR Example

This is an example of how to use ISRs from the PIO on the Raspberry PI Pico.
See `src/main.cpp` for how to enable and respond to ISRs.
See `src/simply_isr.pio` for the assembly to fire a unique ISR per state machine.

## Output
Triggering ISR from state machine 0
Expected IRQ flags: 0x00000001
Actual IRQ Flags: 0x00000001
Triggering ISR from state machine 1
Expected IRQ flags: 0x00000002
Actual IRQ Flags: 0x00000002
Triggering ISR from state machine 2
Expected IRQ flags: 0x00000004
Actual IRQ Flags: 0x00000004
Triggering ISR from state machine 3
Expected IRQ flags: 0x00000008
Actual IRQ Flags: 0x00000008

