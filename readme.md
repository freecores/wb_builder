## Wishbone Bus Builder

This is a clone of opencores wb_builder.
 
From: http://opencores.org/project,wb_builder

### Known errors

- when data bus size is 8 bits the script generates wishbone sel signals which are of no use

### Features

![screenshot](/readme/wb_builder.png?raw=true "Main Menu")

- TK GUI for easy startup
- supports both shared bus and csorrbarswitch topology

### Status

- design tested in HDL simulator and in FPGA (ALTERA C12)
- current design only support VHDL output

### Description

The intention is to provide an easy way to create and change a system based on the WISHBONE bus. The user shall be able to try different configurations to achieve an area/performance optimized design.

WISHBONE builder is a script which generates a wishbone interconnect matrix in HDL. The user defines the functionallity of the wishbone bus in a text file or via a GUI. The tools then generates the HDL implementation.

The core supports both shared bus and crossbar switch implementations.

To run the WISHBONE builder you must have installed PERL. A windows executable can be found at http://www.activestate.com/. In Linux PERL is usually installed with the system. The GUI uses a PERL module called Tk. Tk can be found at CPAN, http://www.cpan.org/. 
