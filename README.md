# PWM_SBUS_converter
Arduino code and hardware design for a simple RC receiver PWM to SBUS converter.

When using modern flight controllers f4+ with betaflight etc, you need to have a RC receiver that uses SBUS or other modern communication protocols. My setup is old and only has PWM output. This converter uses an Arduino Pro mini to translate from old PWM to new SBUS protocol.

![Schematic](/schematic.png)
