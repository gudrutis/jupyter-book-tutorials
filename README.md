# jupyter-book-tutorials
Various tutorials I fallow where i use jupyter book as a platform to learn

To start the Jupyter notebook:

```bash
export MYDIR=$(pwd) #path to this repo on local system
docker run -it -p $MYPORT:8888 -v $MYDIR:/Jupyter adiog/cling-jupyter
```
