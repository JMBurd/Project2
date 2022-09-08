# Project2
Project 2 – Developing a User Interface for a publicly accessible Bioinformatics tool- BWA

The Burrows-Wheeler Aligner (BWA) is a command line bioinformatics tool for mapping short
DNA sequence reads against reference genomes to create alignment files in the binary
alignment file (BAM) format. BWA implements several modules, but in this project, you should
be concerned only with the BWA ‘mem’ command option which accepts input fastq files and a
reference genome and creates a BAM file as the output.

Your goal in the project is to create a use user interface around the tool to be able to analyze (run the ‘mem’ command)  the input data and generate the output.

BWA is available on GitHub https://github.com/lh3/bwa



Pull sequence data from genbank or take it from the computer file in FASTQ format (having browse options). (ncbi SRA ->we can use fastqc command to QC the data and then trim the low quality reads)
BWA requires a index that needs to be made (command: bwa index *insert reference genome file*)
Use Tkinter(python package) to make a GUI and have it have buttons, drop down menus, and entry widgets in it. (found this online : https://tkdocs.com/shipman/)
We can convert the Fastq to a SAM to a BAM file (use BWA to go from fastq to sam, samtools to go form sam to bam)
Do we need to make it so it will recognize if it is on linux/windows and work differently according to OS?
How to address error handling. Do we want to try and have text box notification if something is wrong and the message we want to send with associated error.




Meeting notes:
Language to use: Python has good user interface capabilities. 
We could use discord for better communication : https://discord.gg/xzRBjDFK
Use Tkinter for GUI
Use gitihub to share and edit code
Write psuedocode and post it to Github
Steps:
Get the files (search local computer)
QC files 
Trim low quality reads
Use BWA to read alignments
BWA to turn fastq to SAM
Turn SAM to BAM
Use Ubuntu for the operating system and use conda for python
Set up Ubuntu and familiarize with github by wednesday 
Wednesday 8pm EST & Saturday 11am EST
Check in to ensure everyone has all programs installed
Walk people through troubleshooting if necessary
Start preparing to write the outline
Come up with a timeline for the project
List out objectives/features we want to include
What are our milestones?



Project Outline
outline the goal of the project you are working on and describe the objectives in sufficient detail to demonstrate an understanding
Objectives (From the project description):
Create a use user interface around the tool to be able to analyze (run the ‘mem’ command)  the input data and generate the output.
Get general design of GUI using Kivy in python
Write pseudocode for each respective part and upload to Github
Accept fastq files 
QC fastq files on upload
Read alignment with BWA 
Save SAM file as BAM file using samtools
Print preview of the alignment 
Ask user to select pathway to save BAM file 

a description of the updated objectives you have agreed on with the client required to achieve these goals, including tools/resources to be used and any anticipated problems which may need to be addressed
New Objectives
See if we can access BWA through different command lines
Have a system check to see if the user is using OS or Linux
Create data/input quality checks and data validation functions.
Tools
BioPython
Conda
SamTools
Ubuntu 
Virtual Box
UTM
Anticipated Problems
Interfacing written code to graphic user interface while ensuring data quality is not compromised.
Building a pipeline in Linux

clearly assign each component of work to a team member and show that the project work has been equitably distributed amongst the team.  Provide sufficient detail so it is clear how this breaks down to sub-projects

a timeline of milestones towards meeting each objective
	
