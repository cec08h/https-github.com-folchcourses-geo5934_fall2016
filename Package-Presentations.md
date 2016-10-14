#Python Package Student Presentations

Each student will pick one Python package to present to the class.  The student will have a 20 minute time slot.  15 minutes of that time will be in the form of an Jupyter Notebook based presentation.  The remaining 5 minutes are for questions/discussion.

There are two tables below, one is a list of packages and the other is a list of dates.  Please select BOTH your package and date by editing this page ([how to edit a GitHub wiki page](https://help.github.com/articles/editing-wiki-pages-via-the-online-interface)).  This is first-come-first-served.  Only one student per line in each table. DO NOT EMAIL ME YOUR SELECTION, EDIT THIS PAGE.

You will notice that there are 11 lines in the package table.  I seeded the table with some popular GIS, spatial analysis and graphics packages. You are welcome to choose one of these or pick another one. I'm happy to help you pick a package based on your interests.  You can click the links in the table below to see descriptions of the packages.  You might check out the [Anaconda package page](https://docs.continuum.io/anaconda/pkg-docs) to see what is easily available, or simply Google something like `python remote sensing` or `python agent based modeling`. If you select your own package you must add a line to the table and give a brief description of the package. I retain veto power over any student chosen package.


    | Package | Brief Description | Student
--- | ------- | ----------------- | -------
1. | [basemap](http://matplotlib.org/basemap) | Plot data on map projections with Matplotlib | name
2. | [cartopy](http://scitools.org.uk/cartopy/docs/latest) | Package designed for drawing maps for data analysis and visualization | Ishaan Bhatt
3. | [fiona](https://github.com/Toblerity/Fiona) | Geospatial data abstraction library |  name
4. | [osgeo](http://trac.osgeo.org/gdal/wiki/GdalOgrInPython) | Provides access to the Geospatial Data Abstraction Library (GDAL) | name
5. | [networkx](http://networkx.github.io) | Create, manipulate, and analyze graphs and networks |  Jonathan Hansen
6. | [pyproj](https://code.google.com/p/pyproj/) | Cartographic transformations and geodetic computations |  name
7. | [Shapely](https://github.com/Toblerity/Shapely) | Geometric objects, predicates, and operations |  name
8. | [scipy.spatial](http://docs.scipy.org/doc/scipy/reference/spatial.html) | Spatial algorithms and data structures |  name
10. | [PIL] (http://effbot.org/imagingbook/pil-index.htm) | General image handling and basic image operations |  
11.  | [beautifulsoup4](http://www.crummy.com/software/BeautifulSoup/) | Package designed for screen-scraping | name
12. | [geopy](https://github.com/geopy/geopy) | Client for several popular geocoding web services | name
13. | [pyModis](http://www.pymodis.org) | Package to work with MODIS data | name
14. | [rasterio](https://github.com/mapbox/rasterio) (Mac and Linux only) | Read and write geospatial raster datasets | name
15. | [rasterstats](http://pythonhosted.org/rasterstats/) | For summarizing geospatial raster datasets based on vector geometries | name
16. | [Arcpy](http://pro.arcgis.com/en/pro-app/arcpy/get-started/what-is-arcpy-.htm) | A site package for writing geoprocessing scripts using python in ArcGIS | Atoosa Izadifar
17. | package | description | name
18. | package | description | name
19. | package | description | name
20. | package | description | name
21. | package | description | name


Date    | Student
----    | -------
Nov. 17 | name
        | name
        | name
        | name
        | name
        | name
        | name
Dec. 1  |Alex Carrier
        |Ishaan Bhatt
        |Atoosa Izadifar
        | Jonathan Hansen
        | name
        | name
        | name
Dec. 8  | Hannah King
        | namw
        | name
        | name
        | name
        | name
        | name

#Presentation Content

The goal of your presentation is to **introduce a Python package to your classmates** at a level that will allow them to determine if it might be useful for their work/research.  You will give an overview of the package and show a demo.  For most of you, the **entire presentation will be done in an Jupyter Notebook**.  Come talk to me 7 or more days before your presentation date if you want to use some other technology for your presentation (Keynote, PowerPoint and other similar tools will not be an option).  Come prepared with a **15 minute presentation**, this will give about 5 minutes for questions/answers.

####Deadline:
You must email me (folchcourses@gmail.com) the final version of your presentation (Jupyter Notebook and any supporting files) by **8:00am on the day of your presentation**.  I will push them up to GitHub for everyone to pull for that day's meeting.

####Markdown
The "code" cells in the Jupyter Notebook use regular Python syntax.  The text cells use a syntax called "Markdown".  Markdown is a plain text syntax, which when run through a processing engine can be rendered in a cosmetically pleasing way.  This wiki page for example is written using Markdown as is all the text in Notebooks you study at home.

[This .ipynb file](https://raw.githubusercontent.com/profjsb/python-bootcamp/master/Lectures/04_IPythonNotebookIntroduction/Markdown%20Cells.ipynb) has a bunch of Markdown examples.  Download the Notebook and run it on your person machine.  You can double click a cell to see the Markdown syntax that generates the nice looking output. There are many other Markdown cheat sheets and examples on the internet.


####The general organization for you presentation should be:
 1. High-level description of this package.
   * What is this package?
   * Why does it exist? 
   * Does the package have its own website?
   * Does it work on Windows, Mac and Linux?
 2. Maintenance
   * Who maintains the package?  It's usually a person or people. Are they supported by a university, for-profit company, non-profit company, other?
   * What is the current version of the package? This is usually a number like 1.4.5.
   * When was the last update to the package?
   * Where is the code stored (for example GitHub)?
   * Is the package open source? If so which open-source license are they using?
 3. Installation
   * Did you have to install it, or did it come with Canopy?  If it's not in Canopy give a brief description of how you installed it.
 4. Package demo (**the majority of your presentation**)
   * This will vary widely based on the package and your interests.
   * You can go "wide" and introduce a bunch of tools or go "deep" and show one or two tools in detail.
   * You can borrow from existing online examples and tutorials for the package.  These may be found at the developer's website or other places.
   * Your demo must have working code that you run during the presentation.
 5. Everything else
   * A quick overview of parts of the package that you didn't show.
   * Where people can go to see more examples and demos of the package.