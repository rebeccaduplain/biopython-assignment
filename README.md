# Biopython assignment
This project is fo
Biopython combines of the software of Python for research use in bioinformatics. When working with Ubuntu Terminal you must install Biopython to be able to use it. To install Biopython, you must first have installed Python. Once completed, you can install Biopython using pip install biopython
Note, you may have to install pip prior. 
apt install python-pip
You can verify which version of Biopython was installed by python3 -c "import Bio; print(Bio.__version__)". To run any Python files through the terminal, you must always write python (or python3 depending on the version of Python installed). Each of these scripts in this produce a print

1. Reading Sequence Files in Biopython

Using the following count_fasta.py. This script permits you to count the number of records in each FASTA file. The only thing that needs to be changed is the filename for your desired file. The next script shows the protein length of each record in a FASTA file. Again, all that needs to be edited is the filename __count_record.py__.

2. Checking proteins start with methionine

This next script, check_star_met.py, verifies all protein sequences that start with a methionine represented by the letter M, from the standard IUPAC code and gives a count and prints all the records that do not start with methionine. 

3. Converting a sequence file

There are times where the file you have is not in the format that you want. The script convert.py changes the file format from a GenBank file to a FASTA file.

4. Filtering a sequence file

From there, once the file has been converted to a FASTA format, you can now filter the sequence file. The script, filter.py, 
