# Pierce Walker

Biology student at Glendale Community College (transferring to ASU) and undergraduate research assistant in an
extremophile lab studying *Deinococcus radiodurans*. I'm working toward computational astrobiology, genomics and
bioinformatics. I also run **Neoform Studio**, where I build AI-assisted software and websites, and I keep a home
security lab (Linux, Kali, networking) while working toward CompTIA Security+.

## Featured

### [BioLab Atlas](https://github.com/NeoForm-Studio/biolab-atlas) · [live](https://biolab-atlas-deploy.vercel.app)

Look up a bacterium or archaeon and see what public data exists for it and how much its genome resembles known
extremophiles. A Python pipeline pulls each species from NCBI, UniProt, BacDive and Europe PMC, searches its
proteome for marker genes with BLAST+, and places it among the 100+ species profiled so far. The site pairs this with
a 3D workspace on *D. radiodurans* DNA repair in which every species and gene description cites its source.

### [Athena](https://github.com/NeoForm-Studio/athena-web-builder)

A website-production pipeline with a retro-terminal control bridge: React front end, Node/Express backend that queues
leads, scaffolds sites from a template through an external AI agent, and deploys sites and sends reports. Published as a
reference implementation; building sites needs the external agent tooling described in its README.
