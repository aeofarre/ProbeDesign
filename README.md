# Raj Lab single molecule RNA FISH probe design software
Largely written in MATLAB, sorry.


To run findprobesLocal, you will need to download Bowtie from the following Dropbox link: https://www.dropbox.com/sh/6q1bnpl60r24byz/AAAGFIxAGV4PKK6qmk--8WDZa?dl=0 

If needed, unzip the download, change the name of the folder to 'bowtie' (e.g. bowtie-0.12.7 -> bowtie) and move the folder to one of these paths: /usr/bin/bowtie, $HOME/bowtie, $HOME/Dropbox (RajLab)/probeDesign/bowtie, or $HOME/Downloads/bowtie. On a Mac, you can rename & move a folder in the terminal by typing (for example): mv -R /original/path/bowtie-0.12.7 $HOME/Downloads/bowtie

In the terminal on Mac, you can check the installation by typing: $HOME/Downloads/bowtie -h 
You should see:
"Usage: 
  bowtie [options]* <ebwt> {-1 <m1> -2 <m2> | --12 <r> | <s>} [<hit>]" 
followed by a long list of options

If you see a "permission denied" or "killed" error on a Mac, you'll need to override by navigating to the folder in finder, then open with command-click. After doing so, you should be able to access bowtie in terminal. 

For more info on findprobesLocal, see https://github.com/arjunrajlaboratory/ProbeDesign/blob/04b8485f47b5952eb2cffe9900648d6072d1c603/DesignServer/README_findprobesLocal.txt
