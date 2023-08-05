# CH32V203C8T6

cl.ft: Clock routines.
hsi hse 16i 48i 72e etc.

br.ft: Bit-rate UART routines.
USART1 is used. Tx is PA9 and Rx is PA10.

led.ft: LED routines.
LED1 is on PA8 and LED2 is on PA11.
Also shows use of `ch32v2x.efr` a resource file for 4thcom (https://wiki.forth-ev.de/doku.php/en:projects:e4thcom).

dma.ft: DMA routines.
dma1.en dma1.chrst etc.

test_dma.ft: dma tests.

adc.ft: ADC1 routines.

test_adc.ft: ADC1 tests.
Shows single and scan (multiple) conversions.

tst.ft: tiny test framework.

srcdstvars.ft: declares src and dst variables. Used in testing.
