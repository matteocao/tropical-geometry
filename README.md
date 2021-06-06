# tropical-geometry

## Installation

Pull the docker with
```
docker pull sagemath/sagemath
```
and run it as jupyter notebook from the root folder by
```
docker run -v "${PWD}:/home/sage/volume" -p8889:8888 sagemath/sagemath:latest sage-jupyter
```
and visit `http://localhost:8889` to start playing with the notebook.



