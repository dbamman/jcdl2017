# JCDL 2017 data

Manually annotated dates of first publication for 2,706 books in the HathiTrust Digital Library, in three samples:

* Uniform random sample of books from the public domain (`uniform.txt`, 916 books dated)
* Uniform random sample of books from the ca. 102K automatically identified as fiction by Underwood 2014 (`fiction.txt`, 991 books dated)
* Random sample of books from the public domain, but stratified by observed publication date (roughly equal number of books from each decade between 1750-1922).  (`stratified.txt`, 799 books dated)

This data supports the work described in the following paper:

David Bamman, Michelle Carney, Jon Gillick, Cody Hennesy and Vijitha Sridhar, "[Estimating the Date of First Publication in a Large-Scale Digital Library](http://people.ischool.berkeley.edu/~dbamman/pubs/pdf/jcdl2017.pdf)," JCDL 2017.

---

### Synopsis

Cultural analysis in large-scale digital libraries relies on having an accurate estimate of the dates of text they contain.   For books, however, "date" can be measured in several ways -- from the publication date of a specific manifestation of a work (e.g., a 1920 reprint by D.M. Dent & Sons of a 1906 edition of Jane Austen's Pride and Prejudice) all the way to its date of original composition (for P&P, ~1797).  In this work, we manually identify the date of *earliest publication* for three samples of books from the HathiTrust, exploring the difference between those earliest publication dates and the publication dates recorded in the metadata, and empirically evaluate several methods for estimating the earliest publication date for a work, using both deduplication-based methods and the content of the text itself to make predictions.


---