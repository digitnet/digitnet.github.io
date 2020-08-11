---
layout: page
title: JPEG Toolbox
permalink: /jpeg-toolbox/
---
<br />
<div style="text-align: justify"> The Matlab’s built-in functions used to handle digital images provide only basic conversion between the given JPEG file and image pixels. Thus, they are not effective in dealing with a DCT-based steganographic method since there is no access to the qDCT coefficients. To overcome this issue, we use a dedicated Matlab JPEG Toolbox developed by Phil Sallee. The Sallee’s Toolbox contains special functions allowing to access and manipulate the qDCT coefficients of a given JPEG file.</div>
<br />
<div style="text-align: justify"> The main two functions in the package of Sallee “jpeg_read” and “jpeg_write” perform the steps of the lossless compression applied to the qDCT coefficients, including Huffman coding and decoding. Thus, they provide more functionality, since they give the ability to gain direct access to all the structural elements of a JPEG file from Matlab, including the matrices of qDCT coefficients and the quantization tables.</div>
<br />
#### Toolbox Download:
<div style="text-align: justify">1 - This package is the original one, and it includes pre-compiled MEX binaries (.dll) working under 32-bit systems.</div>
[Phil Sallee's ORIGINAL Toolbox]({{ site.baseurl }}\assets\zip\jpegtbx_1.4.zip) 
<div style="text-align: justify">2 - This package is provided by the Digital Data Embedding Laboratory at the Binghamton University in New York, and it includes pre-compiled MEX binaries for 32-bit and 64-bit systems.</div>
[http://dde.binghamton.edu/download/jpeg_toolbox.zip](http://dde.binghamton.edu/download/jpeg_toolbox.zip)


