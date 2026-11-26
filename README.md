# UltimateXL-Klipper
Klipper configuration files for UltimateXL 3D printer

The host SBC is a BTT Pi v1.2 paired with BTT TFT35 SPI v1.2.1.

The original Duet2 controller is used as a Klipper MCU with original
connections retained as much as possible. UART is used as the
connection interface. On the BTT Pi, pins 8 and 10 are used, and on
the Duet2 the PanelDue RX/TX pins are used.
