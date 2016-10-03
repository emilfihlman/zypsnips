## ARM "standard" cortex debug
ARM made a new "standard" for cortex debug, because smaller is cooler y0. [Read their description of it here](http://infocenter.arm.com/help/topic/com.arm.doc.faqs/attached/13634/cortex_debug_connectors.pdf)

The takeaway is, 2x5, in a _svelte_ 1.27mm pitch  
The common older style is 2x10, but in fatduino 2.54mm pitch.

## Cables

[Olimex 2.54mm->1.27mm adapter](https://www.olimex.com/Products/ARM/JTAG/ARM-JTAG-20-10/) 
(Also available as [Digikey part number: 1188-1016-ND](http://www.digikey.com/product-search/en?keywords=1188-1016-ND))

[Cable only](http://microcontrollershop.com/product_info.php?products_id=4517)


## Board headers

### esden's choice: FTSH-105-01-L-DV-K   (SMT)
not super cheap, (he gets from samtec directly) but it has partial 
shrouding, only around the pins where the key on the cable goes, so it
takes up a lot less space. 
[Digikey partnumber SAM8799-ND](Or just http://www.digikey.com/product-search/en?keywords=SAM8799-ND)

### aandrew's choice: (and other people)
< aandrew> I use the standard everyday fucking used everywhere digikey 1175-1629-nd

* [Digikey 1175-1629-ND (smt)](http://www.digikey.com/product-search/en?keywords=1175-1629-ND)
* [Digikey 1175-1627-ND (pth)](http://www.digikey.com/product-search/en?keywords=1175-1627-ND)

Much much much cheaper, but fully fully shrouded, so more board space.


