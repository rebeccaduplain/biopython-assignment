# Biopython assignment
This project shows bioinformatic functions through the use of Biopython. When working with Ubuntu Terminal you must install Biopython to be able to use it. To install Biopython, you must first have installed Python. Once completed, you can install Biopython using __pip install biopython__
Note: you may have to install pip prior. 
__apt install python-pip__
It is possible to verify which version of Biopython was installed by using __python3 -c "import Bio; print(Bio.__version__)"__. To run any Python files through the terminal, you must always write __python3__ (or __python__ depending on which version of Python was installed). Resulting files were created by adding __> filename.txt__ for every run command.

1. Reading Sequence Files in Biopython

The following __count_fasta.py__. This script permits you to count the number of records in each FASTA file. The only thing that needs to be changed is the filename for your desired file. The next script, __count_record.py__ shows the protein length of each record in a FASTA file. Again, all that needs to be changed is the filename. The result files for __count_fasta.py__ and __count_records.py__ is counts.txt and records.txt respectively.

2. Checking proteins start with methionine

This script, __check_start_met.py__verifies all protein sequences that start with a methionine represented by the letter M from the standard IUPAC code and gives a count and prints all the records that do not start with methionine. The resulting file is titled start_met.txt.

3. Converting a sequence file

It is possible that the file you have is not in the desired format. The script __convert.py__ changes the file format from a GenBank file to a FASTA file. The resulting file is titled NC_000913_converted.fasta.

4. Filtering a sequence file

Once the file has been converted to a FASTA format, you can filter the sequence file. The script, __filter.py__, filters all the sequences that are less than 100 amino acids in length. An output file titled NC_000913_long_only.faa is the output the exclusion of protein sequences less than 100 amino acids long. A result file titled filtered.txt summarizes the number of records selected. 

5. Editing sequences

The script, __edit.py__removes particular sections in sequences. In this case, the script removes the last letter in the protein sequences producing partial sequences. The resulting file is titled PGSC_DM_v3.4_pep_rep_no_stars.fasta.

6. Working with sequence features 

The following two scripts are useful when trying to obtain key properties of sequences in a given file. The first script, __filter_2.py__ goes through a GenBank file and searches for the total number of coding sequences (CDS) present. The resulting file is titled filter_cds.txt. The second script, __total_gene_length.py__, loops over to calculate the total length in the file for all genes on the record. The resulting file is titled filter_length.txt.
