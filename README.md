# SNPTb
Single Nucleotide Polymorphism Transcription Bias
# Steps for Analysis
REQUIRED: Make sure path directories are correct for each step

Install Biopython module using: sudo apt-get install python-biopython

COMMAND: python3 project.py -i /home/path2directory -o fileName -b /home/path2directory -g /home/path2directory/fileName -f /home/path2directory/fileName

-v Path to the vcf file (required)

-b Path to the bamfiles directory (required)

-g Path to the input gtf file (required)

-f Path to the input fasta file (required)

Directory names should end in '/', File names should not end in '/'
