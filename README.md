# Computer Generated Holography Papers
This repository is meant to provie a comprehensive list of papers and algorithms for computer generated holography. The papers are meant to cover a wide range of algorithms, from neuroscience to VR headsets. The categorization of the papers is based on their class, i.e.:
1. Iterative techniques
2. Optimization-based
3. Machine learning-based
4. Deep leanring-based

Each section will begin with a brief description of the class of algorithms discussed, followed by a list of papers and their code/tutorials/etc.
If you want your paper to be featured or have a correction, please create an issue. If you find this repo useful, please hit the start button.

Enjoy!

--------------------------------------
## Iterative Techniques
This class of algorithms rely on an iterative process to directly enforce the amplitude and/or phase conditions of the holographic set up.

[Gerchberg-Saxton](http://www.u.arizona.edu/~ppoon/GerchbergandSaxton1972.pdf) | 
Code: 
[MATLAB](https://www.mathworks.com/matlabcentral/fileexchange/65979-gerchberg-saxton-algorithm) 
[Python](https://github.com/UNC-optics/DeepCGH) | 
[Wikipedia](https://en.wikipedia.org/wiki/Gerchberg%E2%80%93Saxton_algorithm)


[DCGH](https://ieeexplore.ieee.org/document/9417658) | [Code](https://github.com/UNC-optics/DCGH)


## Optimization-based
In this class of algorithms, the solution to the CGH problem (phase and/or amplitude) is directly optimized to minimize a loss function that is aimed to maximize the similarity between the desired output and the hologram that results from the modulation. These algorithms often involve an iterative application of an optimizer to gradually approach a decent solution.

[NOVO-CGH](https://nicolaspegard.com/Publications/optica-NOVOCGH.pdf) | [Code](https://github.com/Waller-Lab/NOVOCGH)


[Wringtinger holography](https://www.cs.unc.edu/~cpk/wirtinger-holography.html) | [Code](https://github.com/dongheon-yoo/Wirtinger-holography)

## Machine learning-based
[Phase retrieval with sparse phase constraint](https://arxiv.org/abs/1804.01878)

## Deep learning-based
[HoloNet (aka DeepCGH for 2D](https://www.osapublishing.org/abstract.cfm?uri=brain-2020-BTu2C.2) | [Code](https://github.com/UNC-optics/DeepCGH)


[DeepCGH](https://www.osapublishing.org/oe/fulltext.cfm?uri=oe-28-18-26636&id=437573) | [Code](https://github.com/UNC-optics/DeepCGH)


[Neural Holography](https://www.computationalimaging.org/publications/neuralholography/) | [Code](https://github.com/computational-imaging/neural-holography)


[Tensor Holography](http://cgh.csail.mit.edu/) | [Code](https://github.com/liangs111/tensor_holography)
