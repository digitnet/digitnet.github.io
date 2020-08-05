---
layout: page
title: Phil Sallee's Toolbox
permalink: /phil-sallee-toolbox/
---

The Matlab’s built-in functions used to handle digital images provide only basic conversion between the given JPEG file and image pixels. Thus, they are not effective in dealing with a DCT-based steganographic method since there is no access to the qDCT coefficients. To overcome this issue, we use a dedicated Matlab JPEG Toolbox developed by Phil Sallee. The Sallee’s Toolbox contains special functions allowing to access and manipulate the qDCT coefficients of a given JPEG file.

The main two functions in the package of Sallee “jpeg_read” and “jpeg_write” perform the steps of the lossless compression applied to the qDCT coefficients, including Huffman coding and decoding. Thus, they provide more functionality, since they give the ability to gain direct access to all the structural elements of a JPEG file from Matlab, including the matrices of qDCT coefficients and the quantization tables.

#### Toolbox Download:


[Phil Sallee's ORIGINAL Toolbox :]({{ site.baseurl }}\assets\zip\jpegtbx_1.4.zip) The package includes pre-compiled MEX binaries (.dll) working under 32-bit systems.

[http://dde.binghamton.edu/download/jpeg_toolbox.zip :](http://dde.binghamton.edu/download/jpeg_toolbox.zip)
This package is provided by the Digital Data Embedding Laboratory in the Binghamton University in New York and it includes pre-compiled MEX binaries for 32-bit and 64-bit systems.


