# Accurate-and-Fast-Multi-view-Face-Landmark-Point-Detection

Created by JongMin Yoon and [Daijin Kim](http://imlab.postech.ac.kr/members_d.htm) at [POSTECH IM Lab](http://imlab.postech.ac.kr)

### Overview
We propose a nobel multi-view face landmark point (LP) detection that operate accurately and rapidly in unconstrained environment. Existing regression based face LP detection methods tend to localize the face landmark points poorly for the sided-poses of face images.l To alleviate this disadvantage, we proposed a nove face LP detection method that generates a good initial shape and uses a mixture of multiple face LP detectors. The proposed face LP detection method consists of five functional stages: 1) a bounding box localizer, 2) an initial shape generator, 3) an ensemble of coarse face LP detectors 4) a shape validator, and 5) a fine face LP detector. 

<img align="left" src= "https://github.com/swdsld/Accurate-and-Fast-Multi-view-Face-Landmark-Point-Detection/blob/master/process.png">

### How to use

- First, you need to unzip trained dataset in 'data'.

- You can detect LP with webcam.

```Shell
test.exe webcam
```

- Or, you can use video file, or image files to detect LP.

```Shell
test.exe video [infile] [outfile]

test.exe images [infolder] [outfolder]
```
### Acknowledgements

