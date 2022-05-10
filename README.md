# Classic-Data-Structure-pt.2
Second classic data structure: Self Organizing Lists

A Self-Organizing list is a list that comes from an improvement from other ordering lists. A self-organizing list improves the process by organizing a list by expected 
frequency of access. The cost to organize such list is cheaper. The improvement lies in the probability of finding K in the front of the list. This process follows the 
80/20 rule where it does 80% of the searches and 20% of the records.

In Self-Organizing Lists there are three different approaches: Count, Move-to-Front, and Transpose. Beginning with Count, it keeps a record of access. Then it orders the 
records by frequency. Lastly, it moves the Highest Frequencies at the front. With Move-to-Front, each time a record is accessed it moves the record to the front of the 
list, hence the name. Lastly, with Transpose, each time a record is being accessed it switches places with the record in front of the other record. 
