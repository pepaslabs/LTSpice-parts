# LTSpice-parts
Parts for LTSpice commonly used by electronics hobbyists (with usage instructions).

LTSpice is a wonderful circuit simulator, but it doesn't include a lot of parts commonly used by hobbyists (e.g. the LM324 op amp), and adding 3rd party parts can be a challenge for newcomers.

**This github project aims to be both a collection of these common "jellybean" components, as well as instructions on how to use them in LTSpice.**

## Parts available in this repo:

* Transistors
  * MOSFETs
    * N-channel, TO-92
      * 2N7000 ([LTSpice tutorial](https://github.com/pepaslabs/LTSpice-parts/wiki/2N7000))
        * [NXP](http://www.nxp.com/documents/spice_model/2N7000.LIB)
        * [On-Semi](http://www.onsemi.com/pub_link/Collateral/2N7000.REV0.LIB)
    * P-channel, TO-92
      * BS250
        * [Philips](http://web.rfoe.net:8000/ziliaoxiazai/PHILIPS/models/spicespar/data/bs250.html)

## Parts built-in to LTSpice (and LT equivalents)
* Transistors
  * BJTs
    * NPN, TO-92
      * 2N3904
        * comes with LTSpice
    * PNP, TO-92
      * 2N3906
        * comes with LTSpice
* Op amps
  * LM358 (dual) / LM324 (quad)
    * The built-in LT-specific (upgraded) equivalent are the LT1013 (dual) / LT1014 (quad)
* Switched-capacitor voltage converters
  * ICL7660
    * The built-in LT-specific (upgraded) equivalent is the LTC1044
