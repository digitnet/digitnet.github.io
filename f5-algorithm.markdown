---
layout: page
title: F5 Algorithm
permalink: /f5-algorithm/
---
<br />
<div style="text-align: justify"> Many of the DCT-based methods are based on the idea of a hash function. The function hashes a specific number (n) of quantized DCT coefficients (qDCT) to produce a specific number (k) of Bits. When the sender wants to embed a secret (k) Bits message, the (n) qDCT coefficients should be modified accordingly. Thus, when the receiver hashes the modified (n) qDCT coefficients, the hidden message is then obtained. The modifications are always constrained by requirements and rules depending on the considered algorithm. </div>
<br />
<div style="text-align: justify"> The F5 algorithm was proposed by Westfeld. It is based on the idea of the matrix encoding (dmax, n, k) with dmax=1, where its goal is to minimize the number of changes made to the qDCT coefficients. The F5 algorithm takes (n) qDCT coefficients and hashes them to (k) Bits using a Xor-based hash function. When the sender needs a modification to embed the secret message, only one coefficient is changed since the resulting (n) qDCT coefficients should not have a hamming distance of more than dmax=1 from the original (n) qDCT coefficients. The (k) and (n) are calculated based on the original image capacity as well as the message length. </div>
<br />
#### F5 Algorithm Matlab Code:
<div style="text-align: justify"> The Matlab code of the F5 algorithm has been published on Github. Also, there is an Ebook published on GRIN explains how the code works: "MATLAB Implementation of the Steganographic Algorithm F5". It is a paid Ebook. Thus, the royalty would be considered as a donation. Students can email the author asking for a free copy. </div>
<br />
Download links:
<br />
[1- F5 Matlab Code Repository on GitHub.](https://github.com/digitnet/f5)
<br />
[2- The Ebook: "MATLAB Implementation of the Steganographic Algorithm F5".](https://www.grin.com/document/464340)
<br />
[3- Westfeld's Paper: "F5-A Steganographic Algorithm: High Capacity Despite Better Steganalysis".]({{ site.baseurl }}\assets\pdf\f5-a-steganographic-algorithm-high-capacity-despite-better-steganalysis.pdf)
<br />
