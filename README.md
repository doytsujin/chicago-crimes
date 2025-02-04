# chicago-crimes

Exploring Chicago crimes dataset with DuckDB, Malloy and new Panel/PyScript data and dashboard tools ...

## Data Source

Data from: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2

**Note:** Chicago crimes data is too large for a github repository. You can download it from the the link above.

![Chicago Crimes 2001 to Present Info ...](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-info.png?raw=true
 "Chicago Crimes 2001 to Present Info ...")

## Raw Data Views

### In VSCode

Raw dataset view in VSCode with [Tabular Data Viewer](https://github.com/RandomFractals/tabular-data-viewer) and [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv):

![Chicago Crimes 2001 to Present Data ...](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-data.png?raw=true
 "Chicago Crimes 2001 to Present Data ...")

### In DBeaver

Crimes `CSV` data imported in [DBeaver](https://dbeaver.io/) for comparison:

![Crimes Data in DBeaver](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-dbeaver.png?raw=true
 "Crimes Data in DBeaver")

### In Tad Viewer

Crimes `CSV` data imported into [Tad Viewer](https://www.tadviewer.com/):

![Crimes Data in Tad Viewer](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-in-tad.png?raw=true
 "Crimes Data in Tad Viewer")

### With Polars

Quick Arrests data query with [Polars](https://www.pola.rs/):

![Chicago Crimes with Polars](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-with-polars.png?raw=true
 "Chicago Crimes with Polars")

### With PyArrow

Loading Chicago crimes raw `CSV` data with [PyArrow](https://arrow.apache.org/docs/python/csv.html):

![Chicago Crimes with PyArrow](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-pyarrow.png?raw=true
 "Chicago Crimes with PyArrow")

### With DuckDB

Loading Chicago crimes `CSV` data into a blank `in-memory` [DuckDB](https://duckdb.org/docs/data/csv) instance:

![Chicago Crimes with DuckDB](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-with-duckdb.png?raw=true
 "Chicago Crimes with DuckDB")

### With DuckDB SQLMagic

Loading Chicago crimes `CSV` data into a blank `in-memory` [DuckDB](https://duckdb.org/docs/guides/python/jupyter) with `ipython-sql` [SQLMagic](https://github.com/catherinedevlin/ipython-sql) in [VSCode Jupyter Notebook](https://code.visualstudio.com/docs/datascience/jupyter-notebooks):

![Chicago Crimes with DuckDB SQLMagic](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-duckdb-sqlmagic.png?raw=true
 "Chicago Crimes with DuckDB SQLMagic")

### In R Studio

Loading Chicago crimes `CSV` data with [DBI](https://dbi.r-dbi.org/) R library and [DuckDB R API](https://duckdb.org/docs/api/r) in [R Studio](https://www.rstudio.com/):

![Chicago Crimes with DuckDB in R](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-duckdb-in-r-studio.png?raw=true
 "Chicago Crimes with DuckDB in R")

### With Julia REPL

Reading Chicago crimes `CSV` data with [DuckDB Julia Package](https://juliahub.com/ui/Packages/DuckDB/89qwz/0.5.1) in [VSCode Julia lang](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia), and running it in [Julia REPL](https://docs.julialang.org/en/v1/stdlib/REPL/):

![Chicago Crimes CSV to DuckDB in Julia REPL](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-duckdb-julia-repl.png?raw=true
 "Chicago Crimes CSV to DuckDB in Julia REPL")

### With Julia CSVFiles and DataFrame

Loading Chicago crimes `CSV` data via Julia [CSVFiles](https://github.com/queryverse/CSVFiles.jl) into native Julia [DataFrames](https://dataframes.juliadata.org/stable/):

![Chicago Crimes CSV in Julia DataFrame](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-csv-julia-dataframe.png?raw=true
 "Chicago Crimes CSV in Julia DataFrame")

### In Emacs

Reading Chicago crimes `CSV` data with [SBCL](https://sbcl.org/) + [cl-duckdb](https://github.com/ak-coram/cl-duckdb) in [Emacs](https://www.gnu.org/software/emacs/) + [SLY](https://github.com/joaotavora/sly):

![Chicago Crimes CSV to DuckDB in Emacs](https://github.com/RandomFractals/chicago-crimes/blob/main/docs/images/chicago-crimes-in-emacs.png?raw=true
 "Chicago Crimes CSV to DuckDB in Emacs")

...

More In & With sections of viewing Chicago crimes data with different open source data tools in the wild to come next weekend

...

## Prior Works

Links to our prior works on [Chicago Crimes EDA](https://twitter.com/search?q=(%23ChicagoCrimes)%20(from%3ATarasNovak)&src=typed_query) circa 2017/2018:

🔗 [Chicago Crimes EDA Summary on Linkedin](https://www.linkedin.com/pulse/chicago-crimes-2017-taras-novak/)

📚 [Chicago Crimes EDA 2017 Jupyter Notebooks](https://github.com/RandomFractals/ChicagoCrimes/tree/master/notebooks)

📚 [Observable JS Chicago Crimes Notebook Collection 2018](https://observablehq.com/@randomfractals/chicagocrimes)

📚 [Chicago Homocides Observable JS Notebook Collection 2018](https://observablehq.com/@randomfractals/leaflet-pixi-overlay?collection=@randomfractals/chicago-homicides)

🐦 [Chicago Crimes EDA, Data Preview and Tabular Data Viewer tweets](https://twitter.com/search?q=(%23ChicagoCrimes)%20(from%3ATarasNovak)&src=typed_query)
