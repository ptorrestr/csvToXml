CSV to LUCENE
=============

Bash Script for parsing TSV files and generate XML needed for Lucene

- csvToXml: Create a XML version of the CSV input file.
- bulkCsvToXml: Parse a complete set of CSV files that find in the input directory.
- bulkSendToLucene: Parse a complete set of CSV file pointed by input directory and send them to Lucene index given by URL
- postLucene: Send a single file to Lucene Index (Note that the lucene index is wrapped by Solr)


Require:
awk.
culr
