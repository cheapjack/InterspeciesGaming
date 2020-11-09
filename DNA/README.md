## DNA Play


Experimenting with visualising the Muscular Dystrophy human genome in text using the terminal.

Text analysis from the command line is a core skill in computer science, and it also is consquently a core skill in bioinformatics. Im interested in how a beginner in the world of bash scripts and the linux or UNIX (MacOS) command line.

If you're interested there's a great tutorial in [linuxcommand](https://linuxcommand.org) and learning Vim [Vim Tutorial](https://www.linux.com/training-tutorials/vim-101-beginners-guide-vim/)


I did some animations above with this [drawHelix](https://github.com/cheapjack/InterspeciesGaming/blob/master/DNA/drawHelix.sh) bash script from [BioSyntax](http://biosyntax.org) which i then screenrecorded with [asciicinema](asciinema.org/) which you can install  via [PipX](https://pypi.org/project/pipx/).

I like how it stays with the trouble of material practices of vim, git, fasta  & bash files in the abstractions and necessary reductions of bioinfomatics. 

### How to use

In the terminal run `drawHelix` which is a bash script which takes a `.fasta` file like [this one which represents a selected region of the human genome](https://www.ncbi.nlm.nih.gov/nuccore/NC_000023.11?report=fasta&from=30786182&to=33672495&strand=true) specific to the mutations with respect to dystrophin and the family of neuromuscular (dis)orders. 

Run from a command line. It's best done in Terminal in OSX or any Linux terminal 

Experimented with the [DMD dystrophin NG_012232 RefSeqGene](https://www.ncbi.nlm.nih.gov/gtr/genes/1756/)

To see the sequence visualised, open a Terminal

Add permissions to `drawHelix.sh` shell script and run

`$ chmod 755 drawHelix.sh`

Display the `.fasta` file to standard OUT 

`$ ./drawHelix filename.fasta` to stream `.fasta` files from Repositories like the [Genetic Testing Registry](https://www.ncbi.nlm.nih.gov/) and visualise them on text 'strands' of DNA

eg. `$ ./drawHelix MuscularDystrophy.fasta` 

Quit with `ctrl` & `c`
