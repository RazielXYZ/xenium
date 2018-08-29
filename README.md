# citissime

Citissime is a collection of concurrent data structures and memory reclamation algorithms.
The data structures are parameterized so that they can be used with various reclamation
schemes (similar to how the STL allows customization of allocators).

This project is based on the previous work in https://github.com/mpoeter/emr

### Data Structures

* Michael Scott queue
* Harris list based set
* Michael Harris hash-map

### Reclamation Schemes

* Lock-Free Reference Counting 
* [Hazard Pointers](http://www.cs.otago.ac.nz/cosc440/readings/hazard-pointers.pdf)
* [Hazard Eras](https://github.com/pramalhe/ConcurrencyFreaks/blob/master/papers/hazarderas-2017.pdf)
* Quiescent State Based Reclamation
* [Epoch Based Reclamation](https://www.cl.cam.ac.uk/techreports/UCAM-CL-TR-579.pdf)
* [New Epoch Based Reclamation](http://csng.cs.toronto.edu/publication_files/0000/0159/jpdc07.pdf)
* [DEBRA](http://www.cs.utoronto.ca/~tabrown/debra/paper.podc15.pdf)
* [Stamp-it](https://arxiv.org/pdf/1805.08639.pdf)
