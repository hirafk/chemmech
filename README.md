# chemmech
A LaTeX package extending chemfig to draw electron pushing arrows (reaction mechanisms) automatically.
ChemFig extension for drawing electron pushing arrows automatically.

## Usage
1. Download `chemmech.sty`.
2. `\usepackage{chemmech}` in your preamble.

## Commands
| Command | Description | Example |
| :--- | :--- | :--- |
| `\bdclev{node1-node2}` | Bond Cleavage | `\bdclev{C1-Br}` |
| `\nuatk{Nu}{node1-node2}` | Nucleophilic Attack | `\nuatk{OH}{C=O}` |
...

See `example.pdf` for more details.
