             TODO: Put logo here.
	  Copyright 2017 / Felix Held

      A small footprint and configurable USB core
                powered by Migen

[> Intro
---------
LiteSDI provides a small footprint and configurable USB core.

LiteSDI is part of LiteX libraries whose aims are to lower entry level of
complex FPGA cores by providing simple, elegant and efficient implementations
of components used in today's SoC such as Ethernet, SATA, PCIe, SDRAM Controller...

The core uses simple and specific streaming buses and will provides in the future
adapters to use standardized AXI or Avalon-ST streaming buses.

Since Python is used to describe the HDL, the core is highly and easily
configurable.

LiteSDI is built using LiteX and uses technologies developed in partnership with
M-Labs Ltd:
 - Migen enables generating HDL with Python in an efficient way.
 - MiSoC provides the basic blocks to build a powerful and small footprint SoC.

LiteSDI can be used as LiteX library or can be integrated with your standard
design flow by generating the verilog rtl that you will use as a standard core.

[> Features
------------
- None

[> Possible improvements
-------------------------
- Lots

[> Getting started
------------------
1. Install Python3 and your vendor's software

2. Obtain LiteX and install it:
  git clone https://github.com/enjoy-digital/litex --recursive
  cd litex
  python3 setup.py install
  cd ..

XXX

[> Simulations:
XXX

[> Tests :
XXX

[> License
-----------
LiteSDI is released under the very permissive two-clause BSD license. Under
the terms of this license, you are authorized to use LiteSDI for closed-source
proprietary designs.
Even though we do not require you to do so, those things are awesome, so please
do them if possible:
 - tell us that you are using LiteSDI
 - cite LiteSDI in publications related to research it has helped
 - send us feedback and suggestions for improvements
 - send us bug reports when something goes wrong
 - send us the modifications and improvements you have done to LiteSDI.

[> Support and consulting
--------------------------

 * [Mailing list](https://groups.google.com/forum/#!forum/photonsdi/join)
 * [IRC Channel](irc://irc.freenode.net/#timvideos) ([Web version](https://webchat.freenode.net/?channels=#photonsdi,#m-labs,#timvideos,#apertus))

We love open-source hardware and like sharing our designs with others.

LiteSDI is developed and maintained by Felix Held for the
[TimVideos](https://code.timvideos.us) & [Apertus](https://apertus.org/)
project.

If you would like to know more about LiteSDI or if you are already a happy
user and would like to extend it for your needs, EnjoyDigital or Felix Held can
provide standard commercial support as well as consulting services.

So feel free to contact us, we'd love to work with you! (and eventually shorten
the list of the possible improvements :)

[> Contact
E-mail: Felix Held <felix [AT] felixheld.de>
E-mail: Florent Kermarrec <florent [AT] enjoy-digital.fr>
