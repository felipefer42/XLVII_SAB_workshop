# Workshop hands-on

The proposed exercise here will guide you through two simple examples using
the [S-PLUS DR4][1]. For the execution of this hands-on, you will follow 
some of the documentation and code examples given during the first part of 
this workshop. In particular, we will use [LSDB][2], [splusdata][3] and some 
common Python libraries like [NumPy][4] (for calculations) and 
[Matplotlib][5] (for plots). In addition to the mentioned technical tools, 
the exercise require data from the the S-PLUS DR4, associated VACs and the 
[GAIA DR3 catalog][6].

## Proposed science cases:

>1. Create a [H.R. Diagram][9] for stars identified by DR4/PSF catalog, 
crossmatching with [GAIA DR3 catalog][6] for the desired region.
>1. Create an [observational galaxy CMD][7] (e.g., *g-r* vs *r*) diagram for 
galaxies identified by the [S-PLUS DR4 QSO/star/galaxy VAC][8], search among
the objects for the big ones to find a galaxy to create an IFS-like cube 
with S-PLUS data using [S-Cubes][13] during the last part of this workshop. 
Right now we just need to save its S-PLUS Field name, coordinates (RA and DEC)
and a guess of the size (in pixels) to create the *SCUBE* with the entire
galaxy.

## Additional information

- For both cases, feel free to search for the celestial coordinates (right
ascencion and declination) used in this hands-on exercise. In order to check
if some coordinate is available at any S-PLUS datarelease, use the
[check coordinate tool][11]. *We will present a list of possible positions
at the beggining of each solution notebook.
- The [S-PLUS DR4][1] provides data for six different appertures (*PStotal*,
*aper_3*, *aper_6*, *auto*, *petro* and *iso*).
> Read more about the different appertures and photometry modes at 
[S-PLUS DR4 paper][1] or [S-PLUS DR4 on-line documentation][10].
- [GAIA DR3][6] has a HiPSCat to use with [LSDB][2] with some limitations.
> Read more about GAIA DR3 HiPSCat: <https://data.lsdb.io/>
- Questions? [S-PLUS DR4 FAQ][12] or send an e-mail to:
[dhubax\@gmail.com](mailto:dhubax@gmail.com?subject=SABWorkshop)

[1]: <https://www.aanda.org/articles/aa/pdf/forth/aa49725-24.pdf> "The Fourth S-PLUS Data Release: 12-filter photometry covering ~3000 square degrees in the southern hemisphere"
[2]: <https://lsdb.readthedocs.io/en/stable/> "Large Survey DataBase python framework"
[3]: <https://github.com/Schwarzam/splusdata> "S-PLUS data python package"
[4]: <https://numpy.org/> "NumPy: scientific computing with Python"
[5]: <https://matplotlib.org/> "Matplotlib: Visualization with Python"
[6]: <https://www.cosmos.esa.int/web/gaia/data-release-3> "GAIA Data Release 3"
[7]: <https://en.wikipedia.org/wiki/Galaxy_color%E2%80%93magnitude_diagram> "Galaxy color-magnitude diagram"
[8]: <https://splus.cloud/documentation/DR4?QSO/star/galaxy_classification> "QSO/star/galaxy classification VAC"
[9]: <https://en.wikipedia.org/wiki/Hertzsprung%E2%80%93Russell_diagram#/media/File:HRDiagram.png> "Observational Hertzsprung-Russel Diagram"
[10]: <https://splus.cloud/documentation/DR4?Photometry> "S-PLUS DR4 on-line documentation"
[11]: <https://splus.cloud/catalogtools/checkc> "S-PLUS check coordinate tool"
[12]: <https://splus.cloud/documentation/DR4?FAQ> "S-PLUS DR4 FAQ"
[13]: <https://elacerda.github.io/s-cubes/> "S-Cubes homepage"