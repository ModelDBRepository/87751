# Source code for the Zilany and Bruce (JASA 2006, 2007) Cat Auditory Nerve Model

This is *Version 2* of the public distribution of the code for the auditory periphery model of:

> [Zilany, M. S. A. and Bruce, I. C. (2006). "Modeling auditory-nerve responses for high sound pressure levels in the normal and impaired auditory periphery," *Journal of the Acoustical Society of America* **120**(3):1446–1466.](http://www.ece.mcmaster.ca/%7Eibruce/papers/papers.htm#PeripheryModels)

and

> [Zilany, M. S. A. and Bruce, I. C. (2007). "Representation of the vowel /e/ in normal and impaired auditory nerve fibers: Model predictions of responses in cats," *Journal of the Acoustical Society of America* **122**(1):402–417.](http://www.ece.mcmaster.ca/%7Eibruce/papers/papers.htm#PeripheryModels)

**Please cite these papers if you publish any research results obtained with this code or any modified versions of this code.**

*The highlights of the improvements in version 2 are:-*

- **Model now runs at sampling rates of 100, 200 and 500 kHz:**
  The major improvement in this version of the code is that it is able
  run at 100 kHz for model fibers with characteristic frequencies (CFs)
  up to 20 kHz. To model fibers up to CFs of 40 kHz, a minimum
  sampling rate of 200 kHz should be used. The flexibility in sampling
  rate is made possible by some changes to the middle-ear filter and
  spike generator code, as described in [readme.txt](http://www.ece.mcmaster.ca/%7Eibruce/zbcatmodel/readme.txt).

- **Improved speed and reduced memory consumption:**
  Running the model at a lower sampling rate produces a major speed
  increase and reduction in memory usage. In addition, the new spike
  generator code is substantially faster than the old method. We have
  also found some savings that can be made in memory allocation.

The code is archived in the following formats:

- A PKZIP-compatible .zip file: [zbcatmodel2007v2.zip](http://www.ece.mcmaster.ca/%7Eibruce/zbcatmodel/zbcatmodel2007v2.zip)
- A .tar.gz file: [zbcatmodel2007v2.tar.gz](http://www.ece.mcmaster.ca/%7Eibruce/zbcatmodel/zbcatmodel2007v2.tar.gz)

The files in both of these archives are identical and are suitable for compiling as a MEX file in Matlab running on either Windows or Unix. See [readme.txt](http://www.ece.mcmaster.ca/%7Eibruce/zbcatmodel/readme.txt) for instructions regarding platform-dependent compiling issues. (This readme file is also included in the .zip and .tar.gz archives.)

[![Return to Home](readme_files/Home)](http://www.ece.mcmaster.ca/%7Eibruce/) [Back to Ian's Home Page](http://www.ece.mcmaster.ca/%7Eibruce/)

---

*Created by Ian Bruce <ibruce@ieee.org> - last modified Thursday, December 20, 2007*

---

2025-05-27 – Standardized to Markdown