# data sources

* NCBI
    * Have data, but need to find out best way to rebuild database locally & want SQL queries to mimic what NCBI taxonomy endpoints do 
    * https://github.com/Bioinfo-Tools/NCBI-taxcollector
    * http://dgg32.blogspot.com/2013/07/map-ncbi-taxonomy-and-gi-into-sqlite.html
    * ftp://ftp.ncbi.nih.gov/pub/taxonomy/
    * BIOSql http://biopython.org/wiki/BioSQL may be way to do this if they already have it worked out, though would require python...
* ITIS
    * We are good to go more or less, though need to setup easy way to automate dataset update, database building locally
    * https://github.com/ropensci/taxize/blob/sql/R/itis.R
    * https://github.com/ropensci/taxize/blob/sql/R/sqlite_init.R
* COL
    * http://www.catalogueoflife.org/content/annual-checklist-archive
    * The dump files from the link above are incomprehensible, just need data...
* ubio
    * haven't found anything yet, maybe avail. if ask
* theplantlist
    * already available, via download csv files
* tropicos
    * haven't found anything yet, maybe avail. if ask
* BOLD
    * http://www.boldsystems.org/index.php/datarelease - but this seems like its just barcode data, not the names database...
