# Computer
We want to build something like the computer in StarTrek which can do complex queries based on natrual language speech.

## Game Plan
#### Step 1
Make a system which can run a comand which is stated as a query
- "What is the length of students?"
#### Step 2
Make a system which can run simple queries that don't need a bunch of joins

## Existing Resources
This is a list of existing attempts to do this which we would do well to use as a jumping off point.

### Papers
- Nguyen, D. Q., Nguyen, D. Q., & Pham, S. B. (2014). Ripple Down Rules for Question Answering, 0, 21. http://doi.org/10.3233/SW-150204
- Androutsopoulos, I., Ritchie, G. D., & Thanisch, P. (1995). Natural Language Interfaces to Databases - An Introduction. Journal of Natural Language Engineering, (709), 50. http://doi.org/10.1017/S0269888900005476
- Li, F., & Jagadish, H. V. (2014). Constructing an Interactive Natural Language Interface for Relational Databases. Proceedings of the VLDB Endowment, 8(1), 73–84. Retrieved from http://www.eecs.umich.edu/eecs/about/articles/2015/VLDB_Best_Paper.pdf

### Packages
- [Natural language to SPARQL Queries](https://github.com/machinalis/quepy)
- Natural language to SQL Queries
	- [Kueri](http://kueri.me)
	- [FriendlyData](https://friendlydata.io)

## Speech to Text
A starting point for speech recognition is [SpeechRecognition](https://pypi.python.org/pypi/SpeechRecognition)
for python. I will edit this document to have notes on how well this tool works and other tools I find.

## Natural Language to Query
This should be populated with ideas from [Existing Resources](#existing-resources)

### Test Cases
- "How many students are there" => students.length

## Example Datasets
Our goal was to start with JSON files, so I have started by populated the example-datasets folder with 
JSON files from [JsonStudio](http://jsonstudio.com/resources/).
- companies.json
- enron.json
- stocks.json
- world_bank.json
- zips.json