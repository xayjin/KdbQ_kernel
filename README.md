# A Jupyter kernel for Kdb/q

No other dependencies beides Jupyter and Q. Easy setup. 

It is probably very rough around the edges, but seems to work. Please report any issues you end up having. 

__Other Existing Kernels__

- [IKdbQ](https://github.com/jvictorchen/IKdbQ)

# Todo

- Multiline support
- Image support?
- Code cleanup
- Implementing code completion. 
- Testing


# Install

This requires IPython 3. Note that `q` must be in your path and `$QHOME` must be correctly defined. 

```
python -m kdbq_kernel.install
```

To make sure it is installed:

```
jupyter kernelspec list
```

To use it, run one of:

```
jupyter notebook
# In the notebook interface, select Kdb/Q from the 'New' menu
jupyter qtconsole --kernel kdbq
jupyter console --kernel kdbq
```

# More Info

More information of Kdb and Q:

- [Q Wiki](https://en.wikipedia.org/wiki/Q_(programming_language_from_Kx_Systems))
- [Reference](http://code.kx.com/q/)

For more details on how this works, also see:

- [Wrapper Kernels](http://jupyter-client.readthedocs.org/en/latest/wrapperkernels.html)
- [Pepect replwrap](http://pexpect.readthedocs.org/en/latest/api/replwrap.html)



# Thanks

This kernel is heavily/entirely based on the [Bash Kernel by takluyver](https://github.com/takluyver/bash_kernel). 