# Project Data #

I will conducting computational analyses to analyze homologous proteins 
across transposon insertion sequencing studies. The organism that I will 
studying are *Gram-negative* and *Gram-positive* bacteria. The reason 
behind studying those kinds of bacteria are that they show a frequent 
threat in medicine as half of these bacteria are resistant to 
antibiotic. But, for the purpose of the study, I will be looking the 
fluorescence activity accross the different baterias and see the 
similarity accross them.

Some bacterias are: *Vibrio fischeri*, *Acinetobacter baumanii*, *Vibrio 
cholerae*, *Bacteroides thetaiotaomicron*, *Porphyromonas gingivalis*, 
*Pseudomonas aeruginosa*, *Staphylococcus aureus* and many others.

---------- 

## 2022.02.16 ##

I had to run the *ClustalW* through the terminal. 

1. I have to look where the *ClustalW* was in the computer which was: `C:\Program Files (x86)\ClustalW2\clustalw2.exe`.
I had to modify the path:
`$ /c/ 'Program Files (x86)'/ClustalW2/clustalw2` -> without the `.exe` and the (`/`) not (`\`). 

2. Once I had the path for *ClustalW2*, you need to go where the file is. For this time was: `C:\Users\Angel\OneDrive\Desktop\botany563\botany-563\primatesAA.fasta`

3. I was able to access it using the terminal, and once I was in that exact path, I run the following command: 
`$ /c/'Program Files (x86)'/ClustalW2/clustalw2 -ALIGN -INFILE=primatesAA.fasta -OUTFILE=primatesAA-aligned.fasta -OUTPUT=PHYLIP`



 CLUSTAL 2.1 Multiple Sequence Alignments




- Sequence format is Pearson
- Sequence 1: Human        493 aa
- Sequence 2: Chimp        493 aa
- Sequence 3: Gorilla      493 aa
- Sequence 4: Orangutan    493 aa
- Sequence 5: Gibbon       494 aa
- Sequence 6: Rhes_cDNA    497 aa
- Sequence 7: Baboon       497 aa
- Sequence 8: AGM          515 aa
- Sequence 9: AGM_cDNA     515 aa
- Sequence 10: Tant_cDNA    515 aa
- Sequence 11: Patas        495 aa
- Sequence 12: Colobus      495 aa
- Sequence 13: DLangur      495 aa
- Sequence 14: PMarmoset    494 aa
- Sequence 15: Tamarin      494 aa
- Sequence 16: Squirrel     494 aa
- Sequence 17: Owl          494 aa
- Sequence 18: Titi         494 aa
- Sequence 19: Saki         494 aa
- Sequence 20: Howler       551 aa
- Sequence 21: Spider       547 aa
- Sequence 22: Woolly       547 aa
- Start of Pairwise alignments
Aligning...

- Sequences (1:2) Aligned. Score:  97
- Sequences (1:3) Aligned. Score:  97
- Sequences (1:4) Aligned. Score:  93
- Sequences (1:5) Aligned. Score:  90
- Sequences (1:6) Aligned. Score:  87
- Sequences (1:7) Aligned. Score:  87
- Sequences (1:8) Aligned. Score:  87
- Sequences (1:9) Aligned. Score:  87
- Sequences (1:10) Aligned. Score:  87
- Sequences (1:11) Aligned. Score:  86
- Sequences (1:12) Aligned. Score:  88
- Sequences (1:13) Aligned. Score:  88
- Sequences (1:14) Aligned. Score:  71
- Sequences (1:15) Aligned. Score:  70
- Sequences (1:16) Aligned. Score:  68
- Sequences (1:17) Aligned. Score:  70
- Sequences (1:18) Aligned. Score:  70
- Sequences (1:19) Aligned. Score:  71
- Sequences (1:20) Aligned. Score:  68
- Sequences (1:21) Aligned. Score:  69
- Sequences (1:22) Aligned. Score:  69
- Sequences (2:3) Aligned. Score:  98
- Sequences (2:4) Aligned. Score:  94
- Sequences (2:5) Aligned. Score:  90
- Sequences (2:6) Aligned. Score:  87
- Sequences (2:7) Aligned. Score:  87
- Sequences (2:8) Aligned. Score:  86
- Sequences (2:9) Aligned. Score:  87
- Sequences (2:10) Aligned. Score:  87
- Sequences (2:11) Aligned. Score:  87
- Sequences (2:12) Aligned. Score:  88
- Sequences (2:13) Aligned. Score:  88
- Sequences (2:14) Aligned. Score:  70
- Sequences (2:15) Aligned. Score:  69
- Sequences (2:16) Aligned. Score:  67
- Sequences (2:17) Aligned. Score:  70
- Sequences (2:18) Aligned. Score:  70
- Sequences (2:19) Aligned. Score:  70
- Sequences (2:20) Aligned. Score:  69
- Sequences (2:21) Aligned. Score:  69
- Sequences (2:22) Aligned. Score:  69
- Sequences (3:4) Aligned. Score:  94
- Sequences (3:5) Aligned. Score:  91
- Sequences (3:6) Aligned. Score:  87
- Sequences (3:7) Aligned. Score:  88
- Sequences (3:8) Aligned. Score:  87
- Sequences (3:9) Aligned. Score:  87
- Sequences (3:10) Aligned. Score:  87
- Sequences (3:11) Aligned. Score:  87
- Sequences (3:12) Aligned. Score:  89
- Sequences (3:13) Aligned. Score:  88
- Sequences (3:14) Aligned. Score:  71
- Sequences (3:15) Aligned. Score:  70
- Sequences (3:16) Aligned. Score:  68
- Sequences (3:17) Aligned. Score:  71
- Sequences (3:18) Aligned. Score:  71
- Sequences (3:19) Aligned. Score:  72
- Sequences (3:20) Aligned. Score:  69
- Sequences (3:21) Aligned. Score:  70
- Sequences (3:22) Aligned. Score:  70
- Sequences (4:5) Aligned. Score:  90
- Sequences (4:6) Aligned. Score:  86
- Sequences (4:7) Aligned. Score:  86
- Sequences (4:8) Aligned. Score:  86
- Sequences (4:9) Aligned. Score:  86
- Sequences (4:10) Aligned. Score:  86
- Sequences (4:11) Aligned. Score:  86
- Sequences (4:12) Aligned. Score:  87
- Sequences (4:13) Aligned. Score:  87
- Sequences (4:14) Aligned. Score:  70
- Sequences (4:15) Aligned. Score:  69
- Sequences (4:16) Aligned. Score:  67
- Sequences (4:17) Aligned. Score:  68
- Sequences (4:18) Aligned. Score:  69
- Sequences (4:19) Aligned. Score:  69
- Sequences (4:20) Aligned. Score:  69
- Sequences (4:21) Aligned. Score:  69
- Sequences (4:22) Aligned. Score:  69
- Sequences (5:6) Aligned. Score:  83
- Sequences (5:7) Aligned. Score:  84
- Sequences (5:8) Aligned. Score:  83
- Sequences (5:9) Aligned. Score:  83
- Sequences (5:10) Aligned. Score:  83
- Sequences (5:11) Aligned. Score:  83
- Sequences (5:12) Aligned. Score:  85
- Sequences (5:13) Aligned. Score:  85
- Sequences (5:14) Aligned. Score:  69
- Sequences (5:15) Aligned. Score:  68
- Sequences (5:16) Aligned. Score:  67
- Sequences (5:17) Aligned. Score:  68
- Sequences (5:18) Aligned. Score:  70
- Sequences (5:19) Aligned. Score:  69
- Sequences (5:20) Aligned. Score:  67
- Sequences (5:21) Aligned. Score:  69
- Sequences (5:22) Aligned. Score:  67
- Sequences (6:7) Aligned. Score:  97
- Sequences (6:8) Aligned. Score:  96
- Sequences (6:9) Aligned. Score:  96
- Sequences (6:10) Aligned. Score:  96
- Sequences (6:11) Aligned. Score:  94
- Sequences (6:12) Aligned. Score:  95
- Sequences (6:13) Aligned. Score:  95
- Sequences (6:14) Aligned. Score:  69
- Sequences (6:15) Aligned. Score:  68
- Sequences (6:16) Aligned. Score:  66
- Sequences (6:17) Aligned. Score:  68
- Sequences (6:18) Aligned. Score:  70
- Sequences (6:19) Aligned. Score:  70
- Sequences (6:20) Aligned. Score:  65
- Sequences (6:21) Aligned. Score:  68
- Sequences (6:22) Aligned. Score:  68
- Sequences (7:8) Aligned. Score:  96
- Sequences (7:9) Aligned. Score:  96
- Sequences (7:10) Aligned. Score:  96
- Sequences (7:11) Aligned. Score:  95
- Sequences (7:12) Aligned. Score:  95
- Sequences (7:13) Aligned. Score:  95
- Sequences (7:14) Aligned. Score:  70
- Sequences (7:15) Aligned. Score:  68
- Sequences (7:16) Aligned. Score:  67
- Sequences (7:17) Aligned. Score:  68
- Sequences (7:18) Aligned. Score:  70
- Sequences (7:19) Aligned. Score:  71
- Sequences (7:20) Aligned. Score:  66
- Sequences (7:21) Aligned. Score:  69
- Sequences (7:22) Aligned. Score:  69
- Sequences (8:9) Aligned. Score:  98
- Sequences (8:10) Aligned. Score:  99
- Sequences (8:11) Aligned. Score:  94
- Sequences (8:12) Aligned. Score:  94
- Sequences (8:13) Aligned. Score:  94
- Sequences (8:14) Aligned. Score:  70
- Sequences (8:15) Aligned. Score:  69
- Sequences (8:16) Aligned. Score:  67
- Sequences (8:17) Aligned. Score:  68
- Sequences (8:18) Aligned. Score:  70
- Sequences (8:19) Aligned. Score:  70
- Sequences (8:20) Aligned. Score:  65
- Sequences (8:21) Aligned. Score:  66
- Sequences (8:22) Aligned. Score:  67
- Sequences (9:10) Aligned. Score:  98
- Sequences (9:11) Aligned. Score:  94
- Sequences (9:12) Aligned. Score:  95
- Sequences (9:13) Aligned. Score:  95
- Sequences (9:14) Aligned. Score:  70
- Sequences (9:15) Aligned. Score:  69
- Sequences (9:16) Aligned. Score:  67
- Sequences (9:17) Aligned. Score:  68
- Sequences (9:18) Aligned. Score:  71
- Sequences (9:19) Aligned. Score:  71
- Sequences (9:20) Aligned. Score:  65
- Sequences (9:21) Aligned. Score:  66
- Sequences (9:22) Aligned. Score:  67
- Sequences (10:11) Aligned. Score:  94
- Sequences (10:12) Aligned. Score:  94
- Sequences (10:13) Aligned. Score:  94
- Sequences (10:14) Aligned. Score:  70
- Sequences (10:15) Aligned. Score:  69
- Sequences (10:16) Aligned. Score:  67
- Sequences (10:17) Aligned. Score:  69
- Sequences (10:18) Aligned. Score:  70
- Sequences (10:19) Aligned. Score:  71
- Sequences (10:20) Aligned. Score:  65
- Sequences (10:21) Aligned. Score:  67
- Sequences (10:22) Aligned. Score:  67
- Sequences (11:12) Aligned. Score:  94
- Sequences (11:13) Aligned. Score:  94
- Sequences (11:14) Aligned. Score:  69
- Sequences (11:15) Aligned. Score:  67
- Sequences (11:16) Aligned. Score:  66
- Sequences (11:17) Aligned. Score:  68
- Sequences (11:18) Aligned. Score:  69
- Sequences (11:19) Aligned. Score:  69
- Sequences (11:20) Aligned. Score:  66
- Sequences (11:21) Aligned. Score:  68
- Sequences (11:22) Aligned. Score:  68
- Sequences (12:13) Aligned. Score:  98
- Sequences (12:14) Aligned. Score:  71
- Sequences (12:15) Aligned. Score:  69
- Sequences (12:16) Aligned. Score:  67
- Sequences (12:17) Aligned. Score:  70
- Sequences (12:18) Aligned. Score:  71
- Sequences (12:19) Aligned. Score:  72
- Sequences (12:20) Aligned. Score:  67
- Sequences (12:21) Aligned. Score:  70
- Sequences (12:22) Aligned. Score:  70
- Sequences (13:14) Aligned. Score:  70
- Sequences (13:15) Aligned. Score:  69
- Sequences (13:16) Aligned. Score:  67
- Sequences (13:17) Aligned. Score:  70
- Sequences (13:18) Aligned. Score:  71
- Sequences (13:19) Aligned. Score:  71
- Sequences (13:20) Aligned. Score:  67
- Sequences (13:21) Aligned. Score:  70
- Sequences (13:22) Aligned. Score:  70
- Sequences (14:15) Aligned. Score:  93
- Sequences (14:16) Aligned. Score:  86
- Sequences (14:17) Aligned. Score:  88
- Sequences (14:18) Aligned. Score:  89
- Sequences (14:19) Aligned. Score:  87
- Sequences (14:20) Aligned. Score:  83
- Sequences (14:21) Aligned. Score:  86
- Sequences (14:22) Aligned. Score:  85
- Sequences (15:16) Aligned. Score:  84
- Sequences (15:17) Aligned. Score:  87
- Sequences (15:18) Aligned. Score:  87
- Sequences (15:19) Aligned. Score:  87
- Sequences (15:20) Aligned. Score:  82
- Sequences (15:21) Aligned. Score:  86
- Sequences (15:22) Aligned. Score:  85
- Sequences (16:17) Aligned. Score:  85
- Sequences (16:18) Aligned. Score:  85
- Sequences (16:19) Aligned. Score:  84
- Sequences (16:20) Aligned. Score:  80
- Sequences (16:21) Aligned. Score:  83
- Sequences (16:22) Aligned. Score:  82
- Sequences (17:18) Aligned. Score:  88
- Sequences (17:19) Aligned. Score:  87
- Sequences (17:20) Aligned. Score:  84
- Sequences (17:21) Aligned. Score:  86
- Sequences (17:22) Aligned. Score:  85
- Sequences (18:19) Aligned. Score:  92
- Sequences (18:20) Aligned. Score:  85
- Sequences (18:21) Aligned. Score:  87
- Sequences (18:22) Aligned. Score:  87
- Sequences (19:20) Aligned. Score:  83
- Sequences (19:21) Aligned. Score:  86
- Sequences (19:22) Aligned. Score:  85
- Sequences (20:21) Aligned. Score:  86
- Sequences (20:22) Aligned. Score:  85
- Sequences (21:22) Aligned. Score:  92
- Guide tree file created:   [primatesAA.dnd]

There are 21 groups 

Start of Multiple Alignment

- Aligning...
- Group 1: Sequences:   2      Score:10695
- Group 2: Sequences:   3      Score:10693
- Group 3: Sequences:   4      Score:10550
- Group 4: Sequences:   5      Score:10317
- Group 5: Sequences:   2      Score:10814
- Group 6: Sequences:   2      Score:11293
- Group 7: Sequences:   3      Score:11222
- Group 8: Sequences:   5      Score:10697
- Group 9: Sequences:   6      Score:10568
- Group 10: Sequences:   2      Score:10784
- Group 11: Sequences:   8      Score:10576
- Group 12: Sequences:  13      Score:9953
- Group 13: Sequences:   2      Score:10473
- Group 14: Sequences:   3      Score:10194
- Group 15: Sequences:   4      Score:10034
- Group 16: Sequences:   2      Score:10399
- Group 17: Sequences:   6      Score:10117
- Group 18: Sequences:   2      Score:11561
- Group 19: Sequences:   3      Score:11013
- Group 20: Sequences:   9      Score:9780
- Group 21: Sequences:  22      Score:8718
- Alignment Score 573733


WARNING: Truncating sequence names to 10 characters for PHYLIP output.


PHYLIP-Alignment file created   [primatesAA-aligned.fasta]

2/16/2022 8:32:31 PM

---------- 

## Sequencing HW Part 2: Choosing your data and performing QC ##

For my final project, I will be using genome data from the NCBI. Per se, I will not be using raw data. However, I will still be using Fast QC in order to have a better quality results. 

### Running phyluce ###

To install phyluce on Windows 10, I had to download Windows Subsystem for Linux (WSL) [instructions: https://docs.microsoft.com/en-us/windows/wsl/install]. 

Steps to download the WSL (https://docs.microsoft.com/en-us/windows/wsl/install):
1. Open the Command line, and then insert this command > wsl --install . 
2. After the command run, I needed to restart my computer. 
3. I found a problem while trying to download phyluce. It turns out I need to download Ubuntu to perform a Linux subsystem.
One error that appeared was: "Error: 0x80370102 The virtual machine could not be started because a required feature is not installed." To correct this problem, I enabled Hyper-V support at BIOS Level by:
	* Restarting the computer 
	* I pressed F10, and waited for the BIOS level. 
	* Go to systems configuration and enable Virtualization. 
	* Then, save and exit. Reboot. 
4. After I changed that, Ubuntu was able to run in my computer. 
5. In order to make the installations easier, I installed Homebrew that allows me to install all the programs needed using the command line. I followed the instructions here: "https://www.how2shout.com/linux/how-to-install-brew-ubuntu-20-04-lts-linux/"
6. Once I completed these steps, I followed the commands and instructions from notebook-log.md (https://github.com/crsl4/phylogenetics-class/blob/master/exercises/notebook-log.md)

## Aligning the data ##

As my project will be focusing on the similarity between species, I will be using T-coffee as it uses consistency-based and is a progressive alignment method. 

Steps:
##### Using ClustalW #####
1. I had to run the *ClustalW* through the terminal. 

1. I have to look where the *ClustalW* was in the computer which was: `C:\Program Files (x86)\ClustalW2\clustalw2.exe`.
I had to modify the path:
`$ /c/ 'Program Files (x86)'/ClustalW2/clustalw2` -> without the `.exe` and the (`/`) not (`\`). 

2. Once I had the path for *ClustalW2*, you need to go where the file is. For this time was: `"C:\Users\Angel\Downloads\Vcholerae1.fasta"`

3. I was able to access it using the terminal, and once I was in that exact path, I run the following command: 
`$ /c/'Program Files (x86)'/ClustalW2/clustalw2 -ALIGN -INFILE=Vcholerae1.fasta -OUTFILE=Vcholerae1-aligned.fasta -OUTPUT=PHYLIP`


##### Using T-Coffee #####
- Install T-Coffee in Ubuntu (WSL system). I used the following commands:
	- `$ sudo apt update`, Enter.
	- Then, `$ sudo apt install t-coffee` and Enter.

- After it got installed in Ubuntu, I was able to detect if T-Coffee was installed by using `$ t_coffee -version`. This was the message that shows that the program was successfully installed: `PROGRAM: T-COFFEE Version_12.00.7fb08c2 (2018-12-11 09:27:12 - Revision 7fb08c2 - Build 211)`.
BOB

#Data Using ClustalW#
1. Sequences:

1. Alignment:
	A. with ClustalW
=== Started Clustal W at 4:40:34 PM ===
Command: C:\Program Files (x86)\DNASTAR\Lasergene 17\MegAlignPro\tools/win64/clustalw2.exe -INFILE=input.fasta -OUTFILE=10812-output_.fasta -OUTPUT=FASTA -DNAMATRIX=IUB -GAPOPEN=10.0 -GAPEXT=0.2 -MAXDIV=30.0 -TRANSWEIGHT=0.5 -PWDNAMATRIX=IUB -PWGAPOPEN=10.0 -PWGAPEXT=0.1



 CLUSTAL 2.1 Multiple Sequence Alignments


Sequence format is Pearson
Sequence 1: 0          14889 bp
Sequence 2: 1          16208 bp
Sequence 3: 2          16225 bp
Sequence 4: 3          16228 bp
Sequence 5: 4          20089 bp
Sequence 6: 5          20331 bp
Sequence 7: 6          15693 bp
Sequence 8: 7          16258 bp
Sequence 9: 8          15479 bp
Sequence 10: 9          15744 bp
Sequence 11: 10         15737 bp
Sequence 12: 11         15733 bp
Start of Pairwise alignments
Aligning...

Sequences (1:2) Aligned. Score:  61
Sequences (1:3) Aligned. Score:  60
Sequences (1:4) Aligned. Score:  61
Sequences (1:5) Aligned. Score:  62
Sequences (1:6) Aligned. Score:  63
Sequences (1:7) Aligned. Score:  51
Sequences (1:8) Aligned. Score:  51
Sequences (1:9) Aligned. Score:  63
Sequences (1:10) Aligned. Score:  64
Sequences (1:11) Aligned. Score:  64
Sequences (1:12) Aligned. Score:  63
Sequences (2:3) Aligned. Score:  83
Sequences (2:4) Aligned. Score:  88
Sequences (2:5) Aligned. Score:  64
Sequences (2:6) Aligned. Score:  73
Sequences (2:7) Aligned. Score:  53
Sequences (2:8) Aligned. Score:  52
Sequences (2:9) Aligned. Score:  57
Sequences (2:10) Aligned. Score:  56
Sequences (2:11) Aligned. Score:  56
Sequences (2:12) Aligned. Score:  56
Sequences (3:4) Aligned. Score:  82
Sequences (3:5) Aligned. Score:  63
Sequences (3:6) Aligned. Score:  74
Sequences (3:7) Aligned. Score:  53
Sequences (3:8) Aligned. Score:  52
Sequences (3:9) Aligned. Score:  57
Sequences (3:10) Aligned. Score:  56
Sequences (3:11) Aligned. Score:  56
Sequences (3:12) Aligned. Score:  57
Sequences (4:5) Aligned. Score:  64
Sequences (4:6) Aligned. Score:  74
Sequences (4:7) Aligned. Score:  53
Sequences (4:8) Aligned. Score:  52
Sequences (4:9) Aligned. Score:  58
Sequences (4:10) Aligned. Score:  57
Sequences (4:11) Aligned. Score:  57
Sequences (4:12) Aligned. Score:  56
Sequences (5:6) Aligned. Score:  55
Sequences (5:7) Aligned. Score:  54
Sequences (5:8) Aligned. Score:  52
Sequences (5:9) Aligned. Score:  72
Sequences (5:10) Aligned. Score:  71
Sequences (5:11) Aligned. Score:  71
Sequences (5:12) Aligned. Score:  72
Sequences (6:7) Aligned. Score:  64
Sequences (6:8) Aligned. Score:  62
Sequences (6:9) Aligned. Score:  71
Sequences (6:10) Aligned. Score:  70
Sequences (6:11) Aligned. Score:  70
Sequences (6:12) Aligned. Score:  69
Sequences (7:8) Aligned. Score:  93
Sequences (7:9) Aligned. Score:  52
Sequences (7:10) Aligned. Score:  52
Sequences (7:11) Aligned. Score:  52
Sequences (7:12) Aligned. Score:  52
Sequences (8:9) Aligned. Score:  51
Sequences (8:10) Aligned. Score:  51
Sequences (8:11) Aligned. Score:  51
Sequences (8:12) Aligned. Score:  51
Sequences (9:10) Aligned. Score:  84
Sequences (9:11) Aligned. Score:  84
Sequences (9:12) Aligned. Score:  84
Sequences (10:11) Aligned. Score:  99
Sequences (10:12) Aligned. Score:  86
Sequences (11:12) Aligned. Score:  86
Guide tree file created:   [C:\Users\Angel\AppData\Local\Temp\DNASTAR\MegAlignPro\Temp\10812_ClustalW-Alignment-Engine_e39ccec0-9915-43e7-8df4-d5bb801296d9_.MegAlignPro\input.dnd]

There are 11 groups
Start of Multiple Alignment

Aligning...
Group 1: Sequences:   2      Score:276483
Group 2: Sequences:   3      Score:258053
Group 3: Sequences:   4      Score:229909
Group 4: Sequences:   2      Score:298718
Group 5: Sequences:   3      Score:267943
Group 6: Sequences:   4      Score:252858
Group 7: Sequences:   5      Score:211953
Group 8: Sequences:   6      Score:179136
Group 9: Sequences:  10      Score:164799
Group 10: Sequences:   2      Score:285546
Group 11: Sequences:  12      Score:140421
Alignment Score 2972481
firstres = 1 lastres = 27378
FASTA file created!

Fasta-Alignment file created    [C:\Users\Angel\AppData\Local\Temp\DNASTAR\MegAlignPro\Temp\10812_ClustalW-Alignments_c8b81682-bc13-45ee-a327-3a43ffbcce06_.MegAlignPro\10812-output_.fasta]


=== Ended Clustal W at 4:47:07 PM after 6.54 minutes ===

