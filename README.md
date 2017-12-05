# gpio_five_buttons_irq_zedboard

This repository included an example of how to use GPIO design and enable irq's on it.

For this I am using gpio 5 buttons implementation in FPGA design. 

# Design

The design is simple, just adding a gpio block and enable PL-PS interrupts on it.

I am using Shared peripheral interrups (SPI) in this design. 

![](images/gpio_irq_design.png?raw=true)

# Versions

Vivado version for this design is 2014.4.

# Target platform

Target platform is zynq 7000 zedboard.

# Compile and run sample

Just use Xilinx SDK with the project is included in this repo and there should not be any problem to make a correct deploy.

Enjoy!

Thanks to https://embeddedcentric.com for inspiration.
