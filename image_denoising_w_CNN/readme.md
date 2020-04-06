Given notebook file will download 5 images from github repository. 
These images will be used to make list of 256x256 grayscale patches.
500 patches will be randomly selected from each images.
Gaussian noise will be added to each patch.

CNN network will try to clean noise frome these patches.
Noisy images will be our training set, and original images will be
our target set.
