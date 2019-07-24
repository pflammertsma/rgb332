RGB332
======

Generates a pure or custom uniform RGB332 palette in Adobe Color Table (.ACT) binary file format.

[See this Wikipedia article](https://en.wikipedia.org/wiki/List_of_monochrome_and_RGB_palettes#3-3-2_bit_RGB) for more information about the RGB 3-3-2 color space.

## Wear OS 2.0 H platform support

This palette is compatible with Wear OS 2.0 H platform requirements for secondary compute resource (SCR) offloading.

## Gamma shift

The custom palette optionally supports applying gamma shift to provide a more visual appealing result. See the remarks below.

## Notes

- See internal details in [`rgb332.cpp`](rgb332.cpp).
- License restrictions of zlib/libpng apply.

## Palette image comparison

Lena original  
![image](https://raw.githubusercontent.com/pflammertsma/rgb332/master/samples/lena-original.jpg)

Classic gamma corrected uniform palette  
![image](https://raw.githubusercontent.com/pflammertsma/rgb332/master/samples/lena-gamma-corrected-uniform-palette.gif)

Classic websafe uniform palette  
![image](https://raw.githubusercontent.com/pflammertsma/rgb332/master/samples/lena-websafe.gif)

RGB332 pure uniform RGB332 palette  
![image](https://raw.githubusercontent.com/pflammertsma/rgb332/master/samples/lena-rgb332-pure.png)

RGB332 custom uniform RGB332 palette  
![image](https://raw.githubusercontent.com/pflammertsma/rgb332/master/samples/lena-rgb332-custom.png)
