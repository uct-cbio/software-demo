# Download/usage

RDP runs well under Windows 95/98/NT/XP/VISTA/7/8 and may/may not run properly under Windows 10. RDP also runs well on most windows emulators. For Mac users PlayOnMac is recommended and for Linux users Wine is recommended. You may download:

## Releases:
 - Full list of releases [here](https://github.com/uct-cbio/software-demo/releases)
 - the most up to date (but still a little unstable) version of the program (RDP5 Beta 5.05 including VB runtimes, accesory apps, LDHat lookup tables and a large 3Seq p-value lookup table)
 - the most up to date stable version of the program (RDP4.101 including VB runtimes, accesory apps, LDHat lookup tables and a large 3Seq p-value lookup table)
 - an old version of the program (RDP3.44 including VB runtimes, accesory apps, LDHat lookup tables and a large 3Seq p-value lookup table)
 - a [user manual](https://github.com/uct-cbio/software-demo/raw/main/pdfs/RDP4Manual.pdf)
 - a very old version of the program, RDP2, that can be used to load and explore older project files (RDP2 and earlier)


### Common problems:

 - If you get a "Can't find dll entry point" error when loading an alignment it may be that you have installed a newer version of the program over an older one and your computer did not permit the installer to replace the file DNA.dll in your Windows/syswow64 directory with a newer version. To fix this problem uninstall the program and manually delete the file dna.dll from the Windows/syswow64 directory. When you reinstall the program it should work fine.
 - If you are a Windows 7/8/10 user you may get an error message something like 'unable to register MFC40.dll' when you install the program. Just ignore it and continue - the program should still work OK. If you do not ignore it, the program will not work at all.
 - If you are a Windows 7/8/10 user you may also get an error message something like 'cannot access CMDLG32.OCX' when you try running the program. Try running the progam "FixCOMDLG32error.bat" in the directory where you installed RDP4 and then try restarting RDP4.
 - RDP3 will not work on any 64 bit versions of Windows.


### Citation

#### Please cite:

 - Martin DP, Murrell B, Golden M, Khoosal A, & Muhire B (2015) RDP4: Detection and analysis of recombination patterns in virus genomes. Virus Evolution 1: vev003 doi: 10.1093/ve/vev003[PDF]

#### Also, if you use any of the following features in RDP4 please cite the appropriate papers:

 - The RDP method: Martin, D. & Rybicki, E. (2000). RDP: detection of recombination amongst aligned sequences. Bioinformatics 16, 562-563.
 - The GENECONV method: Padidam, M., Sawyer, S. & Fauquet, C. M. (1999). Possible emergence of new geminiviruses by frequent recombination. Virology 265, 218-225.
 - The Bootscan/Recscan method: Martin, D. P., Posada, D., Crandall, K. A. & Williamson, C. (2005). A modified bootscan algorithm for automated identification of recombinant sequences and recombination breakpoints. AIDS Res Hum Retroviruses 21, 98-102. [PDF]
 - The MaxChi method: Maynard Smith, J. (1992). Analyzing the mosaic structure of genes. J Mol Evol 34, 126-129.
 - The Chimaera method: Posada, D. & Crandall, K. A. (2001). Evaluation of methods for detecting recombination from DNA sequences: Computer simulations. Proc Natl Acad Sci 98, 13757-13762.
  - The SiScan method: Gibbs, M. J., Armstrong, J. S. & Gibbs, A. J. (2000). Sister-Scanning: a Monte Carlo procedure for assessing signals in recombinant sequences. Bioinformatics 16, 573-582.
  - The 3Seq method: Lam H.M., Ratmann O., Boni M.F.(2018). Improved algorithmic complexity for the 3SEQ recombination detection algorithm. Mol Biol Evol, 35, 247-251.[Home Page]
  - The LARD method: Holmes E.C., Worobey, M. & Rambaut,A. (1999). Phylogenetic evidence for recombination in dengue virus. Mol Biol and Evol 16, 405-409.
  - The Topal/DSS method: McGuire, G. & Wright,F. (2000). TOPAL 2.0: Improved detection of mosaic sequences within multiple alignments. Bioinformatics 16, 130-134.
  - The Phylpro method: Weiller, G.F. (1998). Phylogenetic profiles: a graphical method for detecting genetic recombinations in homologous sequences. Mol Biol Evol 15, 326-335.
  - The VisRD methods: Lemey, P., Lott, M., Martin, D.P. & Moulton, V. (2009). Identifying recombinants in human and primate immunodeficiency virus sequence alignments using quartet scanning. BMC Bioinformatics 10, 126. [PDF]
  - Recombination count matrices: Lefeuvre, P., Lett, J.M., Reynaud, B., Martin, D.P. (2007). Avoidance of protein fold disruption in natural virus recombinants. PLoS Pathog 11:e181. [PDF]
  - Recombination hotspot test: Heath, L., van der Walt, E., Varsani, A. & Martin D.P. (2006). Recombination patterns in aphthoviruses mirror those found in other picornaviruses. J Virol 80, 11827-11832. [PDF]
  - Recombination rate plots: McVean, G. A. T., Myers, S. R., Hunt, S., Deloukas, P., Bentley, D. R. & Donnelly, P. (2004). The Fine-Scale Structure of Recombination Rate   - Variation in the Human Genome. Science 304, 581-584.
  - RMin/LD matrices: McVean, G., Awadalla, P. & Fearnhead, P. (2002). A Coalescent-Based Method for Detecting and Estimating Recombination From Gene Sequences. Genetics 160, 1231-1241.
  - Neighbor joining or least squares trees: Felsenstein, J. (1989). PHYLIP – Phylogeny inference package (version 3.2). Cladistics 5, 164–166.
  - Maximum likelihood trees (PYML): Guindon, S. & Gascuel, O. (2003). A simple, fast, and accurate algorithm to estimate large phylogenies by maximum likelihood. Syst Biol 52, 696-704.
  - Maximum likelihood trees (RAxML): Stamatakis, S. (2006). RAxML-VI-HPC: Maximum likelihood-based phylogenetic analyses with thousands of taxa and mixed models. Bioinformatics 22, 2688–2690.
  - Maximum likelihood trees (FastTree): Price, M. N., Dehal, P. S., Arkin, A.P. (2010) FastTree 2 – Approximately Maximum-Likelihood Trees for Large Alignments. PLoS ONE 5, e9490.
  - Bayesian trees: Ronquist F, Teslenko M, van der Mark P, Ayres DL, Darling A, Höhna S, Larget B, Liu L, Suchard MA, Huelsenbeck JP. 2012. MrBayes 3.2: efficient Bayesian phylogenetic inference and model choice across a large model space. Syst Biol. 61:539-542.
  - Tree topology comparisons or SH matrices: Shimodaira, H. & Hasegawa M. (2001) CONSEL: for assessing the confidence of phlogenetic tree selection. Bioinformatics 17, 1246-1247.
  - RF matrices: Simmonds, P. & Welch, J. (2006). Frequency and dynamics of recombination within different species of human enteroviruses. J Virol 80, 483-493.

##### To be informed about bugs or updates email [Darren Martin](mailto:darrenpatrickmartin@gmail.com).