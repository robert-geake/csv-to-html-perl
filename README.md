# csv-to-html-perl
Convert CSV files to html tables:

This script will takes a CSV file name and an optional -h switch and converts the specified CSV and outputs to STDOUT an HTML table.

Usage:
 csv-to-html [file] [option] > outputfile.html
 
Options:
 -h Use a header row to create <th> elements in your table (if your csv has a header row and the -h switch is not active I'll just put the header row in normal <td>. If you csv does not have a header row and you use the -h switch it will add the first row of the csv in <td>).
 
 
