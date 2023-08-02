# MyRegistry
My private registry for my own packages.
Registry for data is [here](https://github.com/ngiann/MyData).

### Register new package

To register use, e.g:
```
register("/home/nikos/.julia/dev/SparseBlackBox/",registry="MyPrivateRegistry")
```

### Remove package from registry 

Currently, this has to be done manually. 
Simply delete the directory in the present repository that holds the relevant contents.
Also remove the corresponding line from file `Registry.toml`.
