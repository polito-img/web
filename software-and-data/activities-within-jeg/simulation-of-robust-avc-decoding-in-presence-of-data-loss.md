---
author: enrico
comments: false
#date: 2022-10-17 09:41:08+00:00
#layout: single
#link: software-and-data/activities-within-jeg/simulation-of-robust-avc-decoding-in-presence-of-data-loss/
slug: simulation-of-robust-avc-decoding-in-presence-of-data-loss
title: Simulation of Robust AVC Decoding in presence of Data Loss
wordpress_id: 3488
---

**Simulation of Robust AVC Decoding in presence of Data Loss**  
_by Enrico Masala_

This software decodes an AVC-compliant bitstream applying some loss patterns as given in an input file. Please note that the software simulates the data loss (in a pretty realistic way) by operating on the UNCORRUPTED version of the bitstream. This allows to avoid crashes, erroneous output of frames etc. independently of the loss pattern. More details in the technical notes accompanying the software and in the [input document](ftp://vqeg.its.bldrdoc.gov/Documents/VQEG_Boulder_Jan14/MeetingFiles/VQEG_JEG-Hybrid_2014_005_Politecnico_di_Torino_contribution_Simulation_of_Robust_H.264_AVC_Decoding.pdf) of the [VQEG](https://vqeg.org) meeting in Jan 2014 in Boulder,CO (JEG-Hybrid session)

We are making this software available to the research community free
of charge. If you use this software in your research, we kindly ask that
you reference our paper listed below (in which such an approach has
been used):

- E. Masala, A. Vesco, M. Baldi, J.C. De Martin, “Optimized H.264
  Video Encoding and Packetization for Video Transmission Over Pipeline
  Forwarding Networks”, IEEE Transactions on Multimedia, vol. 11, n. 5,
  Aug 2009, pp. 972-985.

As new relevant references will be published this list will be promptly updated.

Please note that this software is meant to be a prototype only, it is
not optimized or fitted to any purposes. This program is distributed in
the hope that it will be useful, but WITHOUT ANY WARRANTY; without even
the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR
PURPOSE.

The error resilient AVC decoding software can be downloaded for free.
Please note that we are unable to provide assistance for the software.

Software download:  
[Version 1.0](http://media.polito.it/down/a0d30742f22f89ed31aad9ecf427a7d8/jm16.1__EM_JEG_v1.0__FINAL.tar.bz2)  
[Version 1.1](http://media.polito.it/down/eaaea81c51fd2bcbf77ce90593e3e3b1/jm16.1__EM_JEG_v1.1__FINAL.tar.bz2)
