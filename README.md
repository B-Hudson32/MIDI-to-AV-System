This project presents the design and implementation of a real-time MIDI audio and video visualization system. The system receives MIDI input via UART, 
parses the data, and displays corresponding musical note letters on a VGA output with octave-based vertical spacing. Simultaneously, it generates audio 
signals from the MIDI notes and outputs them through a PMOD interface. The design addresses challenges such as clock domain synchronization between
UART and system clocks, efficient block RAM usage for sprite storage, and real-time audio-visual synchronization, delivering a modular and 
resource-optimized solution suitable for FPGA implementation.
