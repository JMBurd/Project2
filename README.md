# Project2
Project 2 – Developing a User Interface for a publicly accessible Bioinformatics tool- BWA

The Burrows-Wheeler Aligner (BWA) is a command line bioinformatics tool for mapping short
DNA sequence reads against reference genomes to create alignment files in the binary
alignment file (BAM) format. BWA implements several modules, but in this project, you should
be concerned only with the BWA ‘mem’ command option which accepts input fastq files and a
reference genome and creates a BAM file as the output.

Your goal in the project is to create a use user interface around the tool to be able to analyze (run the ‘mem’ command)  the input data and generate the output.

BWA is available on GitHub https://github.com/lh3/bwa


•	Outline the goal of the project you are working on and describe the objectives in sufficient detail to demonstrate an understanding
Objectives (From the project description):
•	Create a user interface around the Burrows-Wheeler Aligner (BWA) tool to be able to analyze (run the ‘mem’ command) the input data and generate the output.
o	The input data will be a fastq file containing short DNA sequence reads and a fasta file containing the reference genome. 
•	Get general design of GUI using Kivy in python
•	Write pseudocode for each respective part and upload to Github
o	Accept fastq files 
o	QC fastq files on upload
o	Read alignment with BWA 
o	Save SAM file as BAM file using samtools
o	Print preview of the alignment 
o	Ask user to select pathway to save BAM file 


•	A description of the updated objectives you have agreed on with the client required to achieve these goals, including tools/resources to be used and any anticipated problems which may need to be addressed
New Objectives
•	See if we can access BWA through different command lines
•	Have a system check to see if the user is using OS or Linux
•	Create data/input quality checks and data validation functions.
Tools
•	BioPython
•	Conda
•	SamTools
•	Ubuntu 
•	Virtual Box
•	UTM
Anticipated Problems
•	Interfacing written code to graphic user interface while ensuring data quality is not compromised.
•	Building a pipeline in Linux


•	Clearly assign each component of work to a team member and show that the project work has been equitably distributed amongst the team.  Provide sufficient detail so it is clear how this breaks down to sub-projects:
o	Tiffany and JBurd: See if we can access BWA through different command lines
o	David and Mary: Create a system check to see if the user is using OS or Linux
o	Chukwuemeka and Stephanie: Create data/input quality checks and data validation functions.
o	Everyone: Create python UI to prompt at start of method.


•	Timeline of milestones towards meeting each objective:
o	Have pseudocode done by end of week 5
o	GUI planned by end of week 5
o	Have a rough idea of what each of us is gouging to have as input and output along with our pseudocode end of week 5
o	Start of week 6 start writing code and everyone knows the input and output 
o	Week 7 solidify code and piece it together
o	Week 8 finalizing code
o	Week 9 troubleshooting/ additional features
o	Week 10 solidify code and plan presentation

