# bitstring-knitting
The notebook `distance_patterns`contains a visual inspection of distances between bit strings.
The idea is:
* take a string distance
* take the first `n=512`integers sorted
* represent them as bit strings
* compute the distance matrix between them.

You can can find some of the generated patterns below.
*Can you guess which distance corresponds to which picture?*
Here is a clue: there are the Hamming distance, the edition distance (a.k.a. Levenshtein), the Jaccard distance and the 1d wasserstein distance.

All the answers are in the notebook.
If you have problems seeing the notebook, you can go [here](http://nbviewer.jupyter.org/github/remilepriol/bitstring-knitting/blob/master/distance_patterns.ipynb).

![wasserstein](images/wasserstein.png)
![edition](images/levdist.png)
![hamming](images/hamming.png)
![jaccard](images/jaccard.png)
