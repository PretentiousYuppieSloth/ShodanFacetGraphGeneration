### ShodanFacetGraphGeneration
By Ketil.dk 
 
I wanted to get a better understanding of the usage of a API, so shodan seemed like a great place to start.
ShodanFacetBarGeneration.py takes a search chriteria and generates graphs and shares a bit of data
You can give it common shodan search chriteria like net:x.x.x.0/24  or search for a technology like apache, synology, IIS or the like



First get a shodan API key and put it in the config.yml

Data is pullled from Shodan and graphs are generated and saved to Results/SEARCHID directory.  

#####You can use several different shodan search criteria.
###### python ShodanFacetGraphGeneration.py net:x.x.x.0/24	
Port distribution for ip range
###### python ShodanFacetGraphGeneration.py apache		
Port distribution for machines responding to apache keyword




TODO

	Fix horrible security issues (of course they are in here somewhere)
		Actually locate said security issues.
	Create folder based on the name of the search, containing datasets and generated pictures etc.
		+Folder creation done.
		-Datasets not saved yet.
		-Graph Pictures not saved yet.
	Extract data and put it on a csv file for each search.
	Save Summery information to file in same directory as css file.
