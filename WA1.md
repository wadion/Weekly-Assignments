1. wc -c *.fasta | tail -5 | > biggest_5_character_counts.fasta
2. This command line will (1) calculate the number of characters in all .fasta files, (2) find the five .fasta files with the largest character counts (at the bottom of the list), and (3) put them into a .fasta file called "biggest_5_character_counts.fasta"
3. So, the expected input is all the .fasta files and the expected output is a .fasta file with the largest five .fasta files
