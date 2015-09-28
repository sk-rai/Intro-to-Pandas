
# Welcome to Pandas Tutorial


## Quick Start

If you have both `conda` and `git` on your system (otherwise, read the
next section for more detailed instructions):

    $ conda install --yes ipython-notebook matplotlib pandas
    $ git clone https://github.com/brandon-rhodes/pycon-pandas-tutorial.git
    $ cd pycon-pandas-tutorial
    $ build/BUILD.sh
    $ ipython notebook

## Detailed Instructions

You will need Pandas, the IPython Notebook, and Matplotlib installed
before you can successfully run the tutorial notebooks.  The [Anaconda
Distribution](http://continuum.io/downloads) is a great way to get up
and running quickly without having to install them each separately —
running the `conda` command shown above will install all three.

Note that having `git` is not necessary for getting the materials.
Simply click the “Download ZIP” button over on the right-hand side of
this repository’s front page at the following link, and its files will
be delivered to you as a ZIP archive:

https://github.com/brandon-rhodes/pycon-pandas-tutorial

Once you have unpacked the ZIP file, download the following four
[IMDB](https://www.imdb.com/) data files and place them in the
tutorial’s `build` directory:

* ftp://ftp.fu-berlin.de/pub/misc/movies/database/actors.list.gz
* ftp://ftp.fu-berlin.de/pub/misc/movies/database/actresses.list.gz
* ftp://ftp.fu-berlin.de/pub/misc/movies/database/genres.list.gz
* ftp://ftp.fu-berlin.de/pub/misc/movies/database/release-dates.list.gz

To convert these into the CSV files that the tutorial needs, run the
`BUILD.py` script with either Python 2 or Python 3.  It will create the
three CSV files in the `data` directory that you need to run all of the
tutorial examples.  It should take about 5 minutes to run on a fast
modern machine:

    $ python build/BUILD.py

You can then start up the IPython Notebook and start looking at the
notebooks:

    $ ipython notebook

I hope that the recording and the exercises in this repository prove
useful if you are interested in learning more about Python and its data
analysis capabilities!

