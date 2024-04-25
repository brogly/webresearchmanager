# Web Research Manager

This repository will eventually be an upgraded version of Litrl Browser supporting new detectors. You can check back in late summer 2024 when it will likely be released.

### If you use Litrl Browser for research we ask that you cite the following:
Rubin et al., (2019). A News Verification Browser for the Detection of Clickbait, Satire, and Falsified News. Journal of Open Source Software, 4(35), 1208, https://doi.org/10.21105/joss.01208

[![DOI](http://joss.theoj.org/papers/10.21105/joss.01208/status.svg)](https://doi.org/10.21105/joss.01208)

#### The code snapshot for the JOSS paper can be found here:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2588566.svg)](https://doi.org/10.5281/zenodo.2588566)

### The initial archived version of the browser with a DOI, released in 2018, and all other code releases can be found here:
Rubin, Victoria L.; Brogly, Chris; Conroy, Nadia; Chen, Yimin; Cornwell, Sarah E.; Asubiaro, Toluwase V. (2018). litrl/litrl_code: Litrl Browser Experimental 0.12.0.0 Public (Version exp-0.12.0.0). Zenodo. 10.5281/zenodo.2016627.

[![DOI](https://zenodo.org/badge/160725581.svg)](https://zenodo.org/badge/latestdoi/160725581)

## Why not a plugin?
Various plugins have already been attempted in this area. We decided to develop a separate research tool for deception with a simple user interface that allowed for easier real-world testing of our group's previous work.

## System Requirements
- Windows 10 or 11.
- 1280x720 (720p) minimum screen resolution.
- 1920x1080 (1080p) recommended screen resolution.
- Relatively modern quad-core 64-bit CPU.
- 4GB of RAM.

## Installing the software
If you run into issues, try installing the following first:
1) VC++ 2019 redistributable: https://aka.ms/vs/17/release/vc_redist.x64.exe
2) .NET 4.8 runtime: https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer

The installer package for Windows 10 and 11 is available under "Releases." The installer takes a few minutes - please be patient! A lot of work is currently done with a batch script - the command prompt may be open for a few minutes - do not close it. The default install location is your desktop, where one folder and one shortcut will be created (other locations are untested).

## Uninstalling the software
Simply delete the Litrl Browser shortcut and LITRL folder from your desktop. That's it!

## Compiling and running the software
Please see the Development & Build process page on the wiki at https://github.com/litrl/litrl_code/wiki/Development-&-build-process

## Acknowledgments
This research has been funded by the Government of Canada Social Sciences and Humanities Research Council 
(SSHRC) Insight Grant (#435-2015-0065) awarded to Dr. Rubin for the project entitled Digital Deception Detection: 
Identifying Deliberate Misinformation in Online News. 

## References

[CLICKBAIT DATASET 1] Abhijnan Chakraborty, Bhargavi Paranjape, Sourya Kakarla, and Niloy Ganguly. "Stop Clickbait: Detecting and Preventing Clickbaits in Online News Media”. In Proceedings of the 2016 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM), San Fransisco, US, August 2016. (URL: https://github.com/bhargaviparanjape/clickbait)

[CLICKBAIT DATASET 2] Martin Potthast, Tim Gollub, Kristof Komlossy, Sebastian Schuster, Matti Wiegmann, Erika Patricia Garces Fernandez, Matthias Hagen, and Benno Stein. Crowdsourcing a Large Corpus of Clickbait on Twitter. In Proceedings of the 27th International Conference on Computational Linguistics (COLING 2018), pages 1498–1507, August 2018. The COLING 2018 Organizing Committee. (URL: https://webis.de/data/webis-clickbait-17.html)

[SATIRE DATASET 1] Rubin, V. R., Conroy, N. J., Chen, Y. & Cornwell, S. (2016) Fake News or Truth? Using Satirical Cues to Detect Potentially Misleading News. In the Proceedings of the Workshop on Computational Approaches to Deception Detection at the 15th Annual Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies.  (NAACL-CADD2016), San Diego, California, June 17, 2016.

Library licenses can be found in the "licenses" folder.
