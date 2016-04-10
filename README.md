### papilio duo digital audio projects
This is my collection of digital audio projects developed for fpgas using a papilio duo fpga/arduino board. 

This work is published under the MIT license. 

####Digital Audio FPGA Projects
* [i2s_function_generator](https://github.com/newdigate/papilio_duo_i2s/tree/master/i2s_function_generator "i2s_function_generator") 
  * my first basic project which outputs a sine wave though i2s 48kHz @ 24bits/sample stereo. 

#### Requirements
* Software
 * Xilinx ISE (runs from windows or linux, I could not get this running on OSX) or equivalent 
* Hardware
 * FPGA
   * I am using papilio duo, which uses the Xilinx Spartan6 XC9SLX9 FPGA.
 * Digital to Analog IC - you'll need a dac to convert the output I2S bus as an analog audio signal.
   * PCM5102A - I've used DIYINHK $12 special. I prefer it becuase there is no setup required though I2C or SPI and can handle up to stereo 384KHz @ 32 bits/sample. 
  
#### Credits and resources
* Gadget Factory - builders of the Papilio family of FPGA dev kits.
  * http://www.gadgetfactory.net/
  * http://papilio.cc/
* Hamster's guide to FPGAs. 
  * http://hamsterworks.co.nz/mediawiki/index.php/FPGA_course
* Free range factory
  * http://freerangefactory.org/pdf/free_range_vhdl.pdf
  * http://freerangefactory.org/
