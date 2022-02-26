# Installation

```
pip install .[pdf,cairo]
```
This will also include the `pdf` and `cairo` extras.

You may need to specify the name of the boost_python library. You can find this with `find /usr/lib* -name "libboost_python*"`
If the file that you found is named `libboost_python39.so` for instance, then you specify it with

```
BOOST_PYTHON_LIB=boost_python39 pip install .[pdf,cairo]
```

If you also want dev dependencies, add `dev` to the list of extras.

