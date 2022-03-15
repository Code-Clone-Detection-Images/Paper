# Code Clone Detection in the Context of Semantically Equivalent Code

Code clones amount to a significant fraction of today’s software system, resulting in a lot of research regarding the
identification of duplicated code pieces and yielding a large amount of semi-automatic code clone detection tools (CCDT). However,
only some of those tools claim the capability to identify semantically equivalent code clones that differ in syntax. Furthermore, many
CCDTs are unmaintained and undocumented research projects, resulting in challenges when reproducing previous comparative
benchmarking results. Moreover, most previous comparisons restrict themselves to one benchmark using BigCloneBench.
This paper aims to do four things by i) presenting a set of Docker images for a selected set of CCDTs, which eases the reproduction of
previous results, ii) benchmarking the selected CCDTs using accepted answers to the Google Code Jam (assuming they are
semantically equivalent), iii) comparing the results with another benchmark of the code of first-semester computer science
students, and iv ) revealing differences in code clones produced by experienced and beginner programmers. Besides the students’
code used, we make everything available online. We reveal various problems in reproducing existing code cloning benchmarks and find
significant differences in the number of clones detected by different CCDTs.

[<img src="https://github.com/Code-Clone-Detection-Images/Paper/blob/gh-pages/preview-01.png?raw=true" width="400"/>](https://media.githubusercontent.com/media/Code-Clone-Detection-Images/Paper/gh-pages/atsfp-florian.sihler.pdf)