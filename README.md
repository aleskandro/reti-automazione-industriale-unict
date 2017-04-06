## Exercise repository for the Course 'Reti per l'automazione industriale' at University of Catania

#### Unofficial and not verified by the teacher

### Platform-independent setup

* Install STM32CubeMX (http://www.st.com/en/development-tools/stm32cubemx.html)

* Install SW4STM32 (http://www.st.com/en/development-tools/sw4stm32.html)

### Fedora GNU/Linux

To get debug and build working correctly I had to install

```# yum install ncurses-devel arm-none-eabi-gdb openocd```

### Generate the code and import the project in Eclipse

* Let's generate the project with STM32CubeMX and export it for the ToolChain/IDE SW4STM32

* Import the code in Eclipse from Import -> Existing Projects into workspace

* On my Fedora installation I had some issues with the Debug configuration as said in the previous section, so if you have the same right click on the Project -> Debug As -> Debug Configurations; in the Debugger section change the binary associated to OpenOCD and GDB to the ones that you can find, probably in /usr/bin (Be sure you installed them before as I done in the previous section).


