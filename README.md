# Query-Processing-Summer-Project-
This code was written as a part of our Summer Project under Prof. Medha Atre (http://www.cse.iitk.ac.in/users/atrem/). 
We are given a data in the form of a flat file which contains strings and each string is mapped to a integer id(in our project the integer id was the line number) in a one-one fashion.
It answers queries of the form -1) given a string, tell it's corresponding integer id. 2) Given an integer id, tell it's corresponding string.
The data can be very large (we tested it on a data of over 100 GB), and the code answers the queries efficiently. Some stats can be found in the "stats" file.

The project serves as an intermediate component while answering sparql queries.

(parts of B+ Tree code have been taken from https://github.com/zcbenz/BPlusTree)
