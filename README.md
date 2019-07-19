# MassSpec-Analysis

Mass Spectrometers produce .raw files. These can be read by a small handful of programs, such as Thermo's software that runs the mass spec. One commonly used program is MaxQuant. It takes the .raw and a fasta file, then analyses the data. It then returns a folder that contains information in several file types, including .txt. 

After running MaxQuant, one of the files is called proteinGroups.txt. This file contains the reporter intensities listed by protein ID. This file is simplified by removing the other columns. This proteinGroups_simplified file is what these programs take as input. 

When other input files are used, it will be noted.
