# ESM_ProteinPred

A workflow to study the proteomic divergence between human and non-human primates.

Step 1: Retrieve the ESM 6M protein language model from FAIR.

Step 2: Retrieve species protein sequences from Uniprot for canonical cell markers for humans, chimpanzees and macaques.

Step 3: Perform embedding of the sequences using ESM 6M.

Step 4: Calculate cosine differences between each pair of species and order them by divergence.

Step 5: Visualize divergence on heatmap, UMAP and dendrograms.

Discovered 4 cell type marker genes that have human specific divergence:

GFAP (Astrocyte)

VIP (Inhibitory neurons)

TRPM3 (Inhibitory neurons)

RBFOX3

TLE4

MOG (oligodendrocyte)

MBP (oligodendrocyte)
