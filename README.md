# Jupyter + Google EE Mapping

Tutorial from Spatial Seminar course using Jupyter + Python (Shapely + Fiona). This may act as a jumping off point for creating web-based mapping using Google's Earth Engine (<strong>GEE</strong>) API. Can use Python libraries (e.g. Shapely + Fiona) or Javascript (e.g. D3js) for data visualization and interactivity overlaid on GEE's API.

## How To Run

#### Installation

```
    conda create -n eepython python=2.7
    source activate eepython
    conda conda install -y cryptography
    conda install -y simplejson
    pip install earthengine-api
```

Confirm installation:

```
    python -c "import ee; print ee.__version__"
```

Install Jupyter, SciPy, Matplotlib:

```
    conda install jupyter scipy matplotlib
```

If installation errors - go to dir:

```
    pip install earthengine-api

```

Install geospatial packages:

```
    conda install fiona
    conda install shapely
    conda install krb5
    conda install libgdal
    conda install gdal
    conda list
```

May need to upgrade / downgrade packages direction in directory:

```
    pip install shapely --upgrade
    pip install fiona --upgrade
```


#### Activate

Command Line:

```
    conda create -n eepython python=2.7
    source activate eepython
    cd PATH/TO/YOUR/DIR
    jupyter notebook
```

This opens Jupyter notebook serving on <strong>localhost:8888</strong>

## References

*[Python Extensions for GEE](https://gist.github.com/tmcw/3987512)
*[Python Extensions for GEE 2](https://gist.github.com/sgillies/1886782)
*[Python Tutorial for GEE](http://www.macwright.org/2012/10/31/gis-with-python-shapely-fiona.html)
