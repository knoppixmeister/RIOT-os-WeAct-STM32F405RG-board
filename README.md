RIOT os board specification for WeAct STM32F405RGT board

WeAct STM32F405RGT6 board works well with 'stm32f4discovery' board target but its good to have its own board specification.
NOTE: Blue LED works but other configuration (pins, perips, etc.) requires review by more skilled specialist.

1) Instructions

```

git clone https://github.com/RIOT-OS/RIOT.git
cd RIOT/boards

git clone https://github.com/knoppixmeister/RIOT-os-WeAct-STM32F405RG-board.git weact-f405rg
cd ../examples/hello-world

make BOARD=weact-f405rg
make BOARD=weact-f405rg flash

```

2) Enjoy!

---

Usefull links:

RIOT os code base: https://github.com/RIOT-OS/RIOT.git
RIOT os stm32f4discovery board code (borrowed code): https://github.com/RIOT-OS/RIOT/tree/master/boards/stm32f4discovery
