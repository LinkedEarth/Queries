# Querying the LinkedEarth wiki

* [What is the LinkedEarth wiki?](#about)
* [Queries and Jupyter Notebook](#jupyter)
* [Quickstart Guide](#quickstart)
* [Requirements](#req)
* [Further Information](#info)
* [Contact](#contact)
* [License](#license)
* [Disclaimer](#disclaimer)

## <a name = "about"> What is the LinkedEarth wiki? </a>

The LinkedEarth wiki leverages semantic wiki technology to crowdsource the curation and standards development of paleoclimate data. Like traditional wikis, they enable the collaborative authoring of content. Secure access and time-stamped content also enable the tracking of changes and the accountability of users, as well as moderation capabilities by community members of recognized expertise. In contrast to traditional wikis, semantic wikis allow contributors to assign *meaning* to their content, specifying relationships between the objects they describe.

This enables complex queries to be performed on the database, using the [SPAQRL Query language](https://www.w3.org/TR/rdf-sparql-query/).

To learn more about the LinkedEarth wiki, see [this page](http://linked.earth/projects/linkedearth-wiki/).

## <a name = "jupyter"> Queries and Jupyter Notebook </a>

The Jupyter Notebook included in this repository aimed to enable querying the LinkedEarth wiki with no to little coding knowledge (besides installing Python on your computer).

This is Notebook is not meant to replace a full API, which will be in the works soon.

This Notebook allows to query the dataset for the most often searched properties (and combination thereof):

* ArchiveType (e.g. marine sediment, coral, speleothem)
* ProxyObservationType (e.g. D18O, Mg/Ca, TRW)
* InferrecVariableType (e.g. SST, E-P)
* Sensor Genus and Species (e.g. Globigerinoides ruber)
* Interpretation (e.g., sea surface temperature)
* Age (Min/Max/Length of the record)
* Location (Lat/Lon/Altitude)
* Resolution

## <a name = "quickstart"> Quickstart Guide </a>

Jupyter Notebook comes with the Python [Anaconda distribution](https://www.continuum.io/downloads).

1. Open your command line application (Terminal or Command Prompt)

2. Type `jupyter notebook`

3. Using the web interface, navigate to where the Jupyter Notebook was saved on your computer and click on it to open the application.

If you are new to Python and Jupyter Notebook, see our introduction [here](https://github.com/nickmckay/LiPD-utilities/blob/master/Examples/Welcome%20Jupyter%20-%20Quickstart.ipynb).

## <a name="req"> Requirements </a>

Running the Notebook requires to have Python v3.4+ installed on your computer. We are currently exploring other options.

## <a name="info">Further information</a>

GitHub: https://github.com/LinkedEarth/Pyleoclim_util

LinkedEarth: http://linked.earth

Python and Anaconda: http://conda.pydata.org/docs/test-drive.html

## <a name = "contact"> Contact </a>

Please report issues to <linkedearth@gmail.com>

## <a name ="license"> License </a>

The project is licensed under the GNU Public License.

## <a name = "disclaimer"> Disclaimer </a>
This material is based upon work supported by the National Science Foundation under Grant Number ICER-1541029. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the investigators and do not necessarily reflect the views of the National Science Foundation.
