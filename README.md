# Mutagenicity Prediction with Graph Convolutional Networks

[Mutagenic compounds](https://en.wikipedia.org/wiki/Mutagen) have the potential
to induce genetic mutations in living organisms, thereby increasing the risk of
cancer. Detecting mutagenicity is thus a critical endeavour in the field of
biomedicine.

This project explores the use of **Graph Convolutional Networks** (GCNs) to
predict mutagenicity in chemical compounds. Through a rigorous evaluation of
various graph convolutional and pooling techniques on the MUTAG dataset, we find
that GCNs can effectively learn graph representations, achieving high accuracy
in mutagenicity prediction. For details refer to the source code in `main.ipynb`
and the two-page report detailing the experiment setup and findings in
`report.pdf`.

This project was carried out for the course [Deep
Learning in
Biomedicine](https://edu.epfl.ch/coursebook/fr/deep-learning-in-biomedicine-CS-502)
(CS-502) at EPFL. The following graph convolutional layers are implemented in
PyTorch:

- `GraphConv` ([Kipf & Welling, 2017](https://arxiv.org/abs/1609.02907))
- `GraphSAGEConv` ([Hamilton et al., 2017](https://arxiv.org/abs/1706.02216))
- `GATConv` ([Veličković et al., 2018](https://arxiv.org/abs/1710.10903))
- `EdgeConv` (Adapted from [Gong et al., 2018](https://arxiv.org/abs/1809.02709))
