## Questions to ask Neil:

How you got started:

Workflow & Tools

Q1. How do you approach analyzing datasets from labs?

collect samples (single cell -> wet lab -> indiviual cells get tagged into droplets -> DNA further broken down into 120 bp chunks -> use of supercomputers to reassemble puzzles (THIS IS done with C)-> figure out where it is on the genome -> see each cells in the RNA expression, see which cells are similar (usually the same kind of cells) -> we don't label what type of cell it is, we only arrange by RNA expression) -> lots of QC results (quality of the cells are good) (looking for droplets without high mitochodrial reads (if you don't know its a good cell, you call it a droplet)) (high mitochondrial reads -> likely a cell to die) -> QC and how many cell types there are are sent to companies


Q2. What are the most common tools you use to manage and analyze datasets?

VS Code to write most of the code, languages - python and R, javascript. Python for the UMap plots. 

Q3. How do you usually ensure data quality and consistency across different projects?

QC checks - cell doubling, Hb%
2 goals - generate reports and give to collaborater, other goal is to support the other teams (data tracking tool)

Learning & Onboarding

Q4. When you started, how did you learn the data infrastructure here — was it mostly hands-on or documented somewhere?
2013 it started, well established team, tried to combine the research and clinical side
oncopanel, edwin was tech -> joined the team

Q5. What skills or tools would you recommend I focus on next to get better at managing and analyzing clinical datasets?
Python, github, bash linux 

What would you recommend someone new to computational biology focus on first to become more useful in a research setting?
python or R - good beginner. we write code so that people can read that code. C++ is a faster language.

Team & Collaboration

Q7. How do you typically collaborate with teams like sequencing or clinical operations?


Q6. What kind of changes have you seen in how data is managed within CCG since working here?
bioinformatics was a younger field, getting more competitive now 
Hands-on / Growth

Q9. Are there any datasets or types of analyses within CCG that you think are especially good for learning the basics hands-on?
generating lollipop plots (taller the lollipop is, more of a hotspot for a mutation)

/opt/homebrew/Caskroom/miniforge/base