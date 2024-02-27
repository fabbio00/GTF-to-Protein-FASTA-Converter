# GTF to Protein FASTA Converter
This project consists of a Python script designed to convert coding sequences found in a GTF (Gene Transfer Format) file to protein sequences in the FASTA format. The code was developed as part of a university project for `genomic sequence analysis`.

## Overview
The code reads a GTF file that contains genomic annotations, such as coding regions (CDS) and other genomic features. It uses the information provided in the GTF file to extract the CDS sequences, translates them into proteins using the specified genetic code, and produces a FASTA file containing the protein sequences.

## Main Features
- **Extraction** of coding sequences (CDS) from a GTF file.
- **Translation** of CDS sequences into proteins using the genetic code.
- **Formatting** of protein sequences in FASTA format.
- **Handling** of translation frames for coding sequences.
  
## Requirements
- The code was written in Python and requires installation of some standard libraries such as `re` and `pandas`.

## Using
- Make sure you have the input GTF and FASTA files.
- Change the path to the input files in the Python code, if necessary.
- Run the Python script.

## Credits
- [Fabio Marini](https://github.com/fabbio00)

## License
This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
