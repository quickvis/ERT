## Exploratory data Record analysis Toolbox

Last updated: 4 April 2024

### OVERVIEW

The program/software is meant to only be used by qualified professionals who take full reponsibility for their work, understand how to use this software, and understand that there may be bugs/mistakes. All users take full responsibility for all of their work done with this software. By using this software you agree that you take full responsibility for your work and do not hold us liable or responsible for any mistakes we have made or any consequences which result from such mistakes.

This program is a graphical user interface implimentation of a data processing pipeline with a built-in visualization tool. It is intended to assist with selection, processing, scaling, and review of ground-motion record data. Although it was developed for earthquake time history data, it can be applied to other types of time history data, i.e., it's not just for earthquakes.

The program is able to complete a variety of signal processing procedures such as frequency filtering and windowing; for structural analysis, it is able to compute floor design spectra for analysis of appurtenant structures. An assortment of other functionalities are also included.

This program is under active developement and more features are continuously being added. If you have a feature request or find a mistake/bug, please contact us.

### WORKSPACE

You can save and load the state of the program as a .workspace file. This program is provided as a .exe with a license which will expire. Once a license has expired, the software will no longer function. Please contact us and we can help extend your license.

### RECORDS

You can load ground-motion record files from a variety of different file formats, either by selecting individual files or folders of files. Records are extracted from the files and are aggregated together into a single combined dataset with a row for each record. You are able to merge in additional record metadata, as additional columns, by loading in a .csv file and performing a merge operation on selected columns.

### PROCESSING

You can add, edit, and delete processing steps and combine them into a data processing pipeline with multiple intermediate data states. Only outward branching of the data processing pipeline is supported. You can pass the dataset through the processing pipeline by changing the current data state. Saving of the processed records in various file formats is supported.

### VISUALIZATION

You can add multiple figures to visualize the ground-motion records at each step throughout the data processing pipeline. These figures can be linked to specific data states and are only updated to the current data state when directed to. You are able to control most of the aesthetic properties of the figures on a figure-by-figure basis.

Saving of figures as static files (e.g., .png) or as interactive files (.html) is allowed. Interactive files can be opened in a web browser and allow for zooming and panning.

### ACKNOWLEDGEMENTS

This program is based on the concept of a [collection pipeline](https://martinfowler.com/articles/collection-pipeline/) with composable data structures as documented by Martin Fowler.

The creators of this program benefited greatly from the knowledge, insights, and expertise of their friends. We hope you can benefit in turn from this toolbox.

This program makes use of a variety of open source and free projects kindly made available by their authors, these include:

#### Python packages/libraries

- [altgraph](https://altgraph.readthedocs.io/en/latest/)
- [certifi](https://certifi.io/en/latest/)
- [chardet](https://chardet.readthedocs.io/en/latest/)
- [charset-normalizer](https://charset-normalizer.readthedocs.io/en/latest/)
- [colorama](https://pypi.org/project/colorama/)
- [contourpy](https://contourpy.readthedocs.io/en/latest/)
- [cycler](https://matplotlib.org/cycler/)
- [decorator](https://github.com/micheles/decorator)
- [exceptiongroup](https://docs.python.org/3/library/exceptions.html#ExceptionGroup) (Standard Library in Python 3.11+)
- [fonttools](https://fonttools.readthedocs.io/en/latest/)
- [future](https://python-future.org/)
- [greenlet](https://greenlet.readthedocs.io/en/latest/)
- [h5py](https://docs.h5py.org/en/stable/)
- [idna](https://github.com/kjd/idna)
- [iniconfig](https://pypi.org/project/iniconfig/)
- [Jinja2](https://jinja.palletsprojects.com/)
- [joblib](https://joblib.readthedocs.io/en/latest/)
- [kiwisolver](https://kiwisolver.readthedocs.io/en/latest/)
- [konnoohmachi](https://github.com/obspy/obspy/wiki)
- [llvmlite](https://llvmlite.readthedocs.io/en/latest/)
- [lml](https://lml.readthedocs.io/en/latest/)
- [lxml](https://lxml.de/)
- [Markdown](https://python-markdown.github.io/)
- [MarkupSafe](https://pypi.org/project/MarkupSafe/)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [mpld3](http://mpld3.github.io/)
- [Nuitka](https://nuitka.net/)
- [numba](https://numba.pydata.org/)
- [numpy](https://numpy.org/doc/)
- [oauthlib](https://oauthlib.readthedocs.io/en/latest/)
- [obspy](https://docs.obspy.org/)
- [packaging](https://packaging.pypa.io/en/latest/)
- [pandas](https://pandas.pydata.org/)
- [pandocfilters](https://github.com/jgm/pandocfilters)
- [patsy](https://patsy.readthedocs.io/en/latest/)
- [pefile](https://pefile.readthedocs.io/en/latest/)
- [Pillow](https://pillow.readthedocs.io/en/stable/)
- [pluggy](https://pluggy.readthedocs.io/en/latest/)
- [py-splash](https://pypi.org/project/py-splash/)
- [pyexcel](https://pyexcel.readthedocs.io/en/latest/)
- [pyexcel-io](https://pyexcel-io.readthedocs.io/en/latest/)
- [PyInstaller](https://pyinstaller.readthedocs.io/en/stable/usage.html)
- [pyinstaller-hooks-contrib](https://github.com/pyinstaller/pyinstaller-hooks-contrib)
- [pyparsing](https://pyparsing-docs.readthedocs.io/en/latest/)
- [PyQt5](https://www.riverbankcomputing.com/static/Docs/PyQt5/)
- [PyQt5-Qt5](https://www.riverbankcomputing.com/static/Docs/PyQt5/)
- [PyQt5-sip](https://www.riverbankcomputing.com/software/sip/intro)
- [pyRVT](https://github.com/arkottke/pyrvt)
- [pytest](https://docs.pytest.org/en/stable/)
- [python-dateutil](https://dateutil.readthedocs.io/en/stable/)
- [pytz](https://pythonhosted.org/pytz/)
- [pywin32-ctypes](https://github.com/enthought/pywin32-ctypes)
- [PyYAML](https://pyyaml.org/wiki/PyYAMLDocumentation)
- [qcore](https://github.com/quantopian/qcore)
- [requests](https://requests.readthedocs.io/en/latest/)
- [requests-oauthlib](https://requests-oauthlib.readthedocs.io/en/latest/)
- [scipy](https://docs.scipy.org/doc/scipy/reference/)
- [seaborn](https://seaborn.pydata.org/introduction.html)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [sqlparse](https://sqlparse.readthedocs.io/en/latest/)
- [squarify](https://pypi.org/project/squarify/)
- [statsmodels](https://www.statsmodels.org/stable/index.html)
- [texttable](https://pypi.org/project/texttable/)
- [threadpoolctl](https://github.com/joblib/threadpoolctl)
- [tinyaes](https://pypi.org/project/tinyaes/)
- [tomli](https://tomli.readthedocs.io/en/latest/)
- [urllib3](https://urllib3.readthedocs.io/en/latest/)
- [wxPython](https://www.wxpython.org/)
- [zstandard](https://pypi.org/project/zstandard/)
  """

unused_txt = """

#### Python packages/libraries

- [obspy](https://docs.obspy.org/)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [wxPython](https://www.wxpython.org/)
- [Pandas](https://pandas.pydata.org/)
- [PyInstaller](https://pyinstaller.readthedocs.io/en/stable/usage.html)
- [seaborn](https://seaborn.pydata.org/introduction.html)

#### Open source python projects

- [SciencePlots](https://github.com/garrettj403/SciencePlots)
- [matplotlib-stylesheets](https://github.com/dhaitz/matplotlib-stylesheets)
- [squarify](https://github.com/laserson/squarify)

#### Free software

- [Inno Setup](https://jrsoftware.org/isinfo.php)
- [Nuitka](https://nuitka.net/)
