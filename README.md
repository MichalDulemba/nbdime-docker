# nbdime-docker
Docker with nbdime (jupyter notebook diff tool)

# Run
(sudo) docker run -it -p 8080:8080 -v ~/:/app  dulemba/nbdime-docker bash

# Diff
nbdiff-web -w test -p 8080 1.ipynb 2.ipynb 

