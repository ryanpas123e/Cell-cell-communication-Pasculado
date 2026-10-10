# Cell-Cell-Communication

## Proposed Signaling Between Hypothalamic GnRH Neurons and Receiving Cells

### Biological Question

Can a signal produced by hypothalamic GnRH neurons communicate with a receiving cell and regulate its intracellular signaling and cellular response?

| Item | Answer |
|---|---|
| Sender cell | Hypothalamic GnRH neuron |
| Biological context | Reproductive endocrine regulation |
| Main purpose | To investigate how a signal from hypothalamic GnRH neurons communicates with another cell and regulates its cellular response. |

## Chosen Sender Cell and Biological Context

| Item | Answer |
|---|---|
| Sender cell | Hypothalamic gonadotropin-releasing hormone (GnRH) neuron |
| Organism | *Homo sapiens* |
| Biological context | Reproductive endocrine regulation |
| Biological role | Hypothalamic GnRH neurons participate in regulating reproductive hormone secretion through communication with other cells in the neuroendocrine system. |

## Candidate Signal and Evidence for Sender-Cell Expression

| Item | Information |
|---|---|
| Sender cell | Hypothalamic GnRH neuron |
| Candidate gene | GNRH1 |
| Protein/peptide name | Gonadotropin-releasing hormone 1 (GnRH) |
| Signal type | Peptide hormone |
| Expression evidence | The Human Protein Atlas reports GNRH1 expression in hypothalamic neuronal cells and neuronal projections. This supports its association with hypothalamic neurons but does not, by itself, establish expression specifically in GnRH neurons. |
| Source | [Human Protein Atlas — GNRH1](https://www.proteinatlas.org/ENSG00000147437-GNRH1) |

### Receptor and receiver cell with supporting evidence

| **Item** | **Information** |
|---|---|
| **Ligand** | GnRH (Gonadotropin-releasing hormone), encoded by *GNRH1* |
| **Receptor** | GnRH receptor (GnRHR), encoded by *GNRHR* |
| **Receiver cell** | Anterior pituitary gonadotroph cell |
| **Signaling type** | Proposed endocrine signaling |
| **Signaling context** | GnRH/GNRHR signaling involving intracellular G-protein signaling and regulation of luteinizing hormone (LH) and follicle-stimulating hormone (FSH) secretion |
| **Supporting source** | [OmniPath — GNRH1 interactions](https://explore.omnipathdb.org/search?q=GNRH1%2C&tab=interactions&species=9606) |
| **Expression/context source** | [Human Protein Atlas — GNRHR](https://www.proteinatlas.org/ENSG00000109163-GNRHR) |

The anterior pituitary gonadotroph cell was selected as the receiver because it expresses the GnRH receptor (GNRHR), which allows it to respond to GnRH released by hypothalamic GnRH neurons. This communication regulates LH and FSH secretion, connecting hypothalamic signaling with reproductive endocrine function.
GNRH1 is a candidate signaling gene because its product is associated with reproductive endocrine regulation. The Human Protein Atlas provides expression information that can help evaluate its suitability as a candidate signal produced by the selected sender cell.
## OmniPath Evidence

| **Component** | **Gene** | **Role** |
|---|---|---|
| GnRH (gonadotropin-releasing hormone) | GNRH1 | Ligand/signal |
| GnRH receptor | GNRHR | Receptor on receiver cell |

OmniPath identified a directed interaction from GNRH1 to GNRHR in *Homo sapiens*. The interaction page displayed 36 references and listed sources including Baccin2019, CellCall, and CellChatDB. This supports the proposed GNRH1–GNRHR relationship for further investigation of GnRH signaling.
## STRING Network Image and Interpretation

| **Item** | **Information** |
|---|---|
| **Enriched process** | To be confirmed using STRING Functional Enrichment |
| **Relevant pathway** | GnRH receptor-associated G-protein signaling |
| **Number of proteins** | 11 visible in the network screenshot |
| **Observed edges** | To be recorded from STRING |
| **PPI enrichment p-value** | To be recorded from STRING |
| **Protein 1** | GNAQ – G-protein signaling component associated with receptor-mediated intracellular signaling |
| **Protein 2** | GNA11 – G-protein alpha subunit involved in intracellular signal transduction |
| **Protein 3** | GNAS – G-protein alpha subunit involved in signal transduction |
| **Protein 4** | GNGT2 – G-protein gamma subunit associated with G-protein signaling |
| **Protein 5** | GNG13 – G-protein gamma subunit associated with G-protein signaling |

The STRING network was generated using GNRHR as the receptor-centered protein. The network contained 11 visible proteins, including G-protein signaling components such as GNAQ, GNA11, GNAS, GNGT2, and GNG13. These proteins may help connect GnRH receptor activation to intracellular signal transduction. Other proteins in the network included GNRH1, GNRH2, KISS1, and KISS1R, which are associated with reproductive hormone signaling. The network therefore supports further investigation of G-protein-associated signaling around GNRHR. Relevant proteins selected for the final model were GNAQ, GNA11, GNAS, and GNG13. 

## IntAct Validation
| **Item** | **Information** |
|---|---|
| **Protein pair examined** | GNRHR – CAMK1D |
| **IntAct record** | [EBI-21894414](https://www.ebi.ac.uk/intact/details/interaction/EBI-21894414) |
| **Interaction type** | Physical association |
| **Experimental detection method** | Anti-tag coimmunoprecipitation |
| **Host organism** | *Homo sapiens* HEK293T embryonic kidney cell |
| **Positive interaction** | Yes |
| **Publication** | Huttlin et al. (2017), *Architecture of the human interactome defines protein communities and disease networks* |
| **Journal** | *Nature* |
| **Publication reference** | [PubMed: 28514442](https://pubmed.ncbi.nlm.nih.gov/28514442/) |
| **Evidence conclusion** | Supports a reported physical association; direct binding is not established by this record alone. |

### Interpretation of the Experimental Evidence

The IntAct record reports a physical association between GNRHR and CAMK1D detected by anti-tag coimmunoprecipitation in human HEK293T cells. Although this supports an experimentally observed association, it does not prove direct binding or confirm that the interaction occurs in pituitary gonadotroph cells during GnRH signaling.

## Final model and interpretation
This model proposes that hypothalamic GnRH neurons communicate with anterior pituitary gonadotrophs through GNRH1–GNRHR signaling. GnRH, encoded by GNRH1, is the proposed extracellular signaling molecule released by hypothalamic neurons. OmniPath supports the directed interaction between GNRH1 and GNRHR, while the anterior pituitary gonadotroph provides a biologically plausible receiving-cell context for GnRH signaling.

After receptor activation, the proposed pathway involves G-protein signaling through Gq/11 and phospholipase C (PLCβ), leading to the production of IP3 and DAG, calcium mobilization, and protein kinase C (PKC) activation. These signaling events contribute to the regulation of luteinizing hormone (LH) and follicle-stimulating hormone (FSH) synthesis and secretion. The STRING analysis identified G-protein-associated candidates, including GNAQ, GNA11, and GNAS. IntAct also reported a physical association between GNRHR and CAMK1D, detected by anti-tag coimmunoprecipitation in human HEK293T cells. However, this finding does not establish direct binding or confirm that the association occurs in pituitary gonadotrophs.

Therefore, the overall model combines database-supported observations with biological inference. The evidence supports the GNRH1–GNRHR relationship and a reported GNRHR–CAMK1D association, while the complete intracellular pathway is based on established biological mechanisms rather than the STRING network alone. Further experiments would be needed to confirm the complete signaling pathway specifically in the proposed sender–receiver cell system.

## Laboratory Activity Questions
**1. What sender cell did you choose, and in what tissue or biological context does it act?**

- Hypothalamic GnRH neuron, acting in reproductive endocrine regulation by releasing gonadotropin-releasing hormone (GnRH), which signals to anterior pituitary gonadotrophs.

**2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?**

- GnRH, encoded by **GNRH1. The Human Protein Atlas (HPA) provides information associating GNRH1 with hypothalamic neuronal expression, supporting its selection as the candidate ligand.

**3. What receptor receives the signal, and which receiver cell did you select?**

- GNRHR receives GnRH. The selected receiver cell is an anterior pituitary gonadotroph, where GnRH signaling contributes to the regulation of luteinizing hormone (LH) and follicle-stimulating hormone (FSH) synthesis and secretion.

**4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?**

- Endocrine signaling, more specifically neuroendocrine signaling. GnRH released by hypothalamic neurons travels through the hypophyseal portal circulation to reach anterior pituitary gonadotrophs.

**5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.**

- GNAQ and GNA11 are relevant candidates because their encoded G-protein alpha subunits are associated with Gq/11 signaling, which can activate phospholipase C-beta (PLCβ). GNAS also appeared in my STRING network as a G-protein-associated candidate. However, the network alone does not establish the specific function of every protein in the selected receiver cell.

**6. What enriched pathway or biological process is consistent with your proposed mechanism?**

- The proposed mechanism is consistent with Gq/11–PLCβ signaling and calcium-mediated regulation of gonadotropin secretion**. GnRH receptor activation can stimulate PLCβ, generating IP3 and DAG. IP3 promotes calcium release from intracellular stores, while DAG contributes to protein kinase C (PKC) activation. These mechanisms are supported by published literature. A specific STRING-enriched pathway, FDR, or enrichment p-value cannot be reported without verifying the enrichment results from my own STRING analysis.

**7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?**

- IntAct record EBI-21894414 reports a physical association between GNRHR and CAMK1D, detected using anti-tag coimmunoprecipitation in human HEK293T cells. The record is associated with Huttlin et al. (2017), PMID 28514442. This supports a reported physical association but does not establish direct binding or confirm that the interaction occurs in anterior pituitary gonadotrophs.

**8. Which parts of your final model are strongly supported, and which parts remain an inference?**

- Strongly supported by the selected database records: OmniPath reports the GNRH1–GNRHR ligand–receptor relationship, while IntAct reports a physical association between GNRHR and CAMK1D. Supported by published literature: Gq/11–PLCβ signaling, calcium mobilization, and the involvement of these mechanisms in gonadotropin regulation. Inferred in my model: The complete signaling sequence occurring in the selected sender–receiver cell pair and the resulting LH and FSH response, because the database records do not independently demonstrate every step in these specific cells.

**9. What cellular response is expected in the receiver cell, and why?**

- Regulation of LH and FSH synthesis and secretion. GnRH binding to GNRHR initiates intracellular signaling that contributes to gonadotropin regulation, supporting reproductive endocrine function.


## References

Durán-Pastén, M. L., & Fiordelisio, T. (2013). GnRH-induced Ca2+ signaling patterns and gonadotropin secretion in pituitary gonadotrophs: Functional adaptations to both ordinary and extraordinary physiological demands. *Frontiers in Endocrinology, 4*, Article 127. https://doi.org/10.3389/fendo.2013.00127

Huttlin, E. L., Bruckner, R. J., Paulo, J. A., Cannon, J. R., Ting, L., Baltier, K., Colby, G., Gebreab, F., Gygi, M. P., Parzen, H., Szpyt, J., Tam, S., Zarraga, G., Pontano-Vaites, L., Swarup, S., White, A. E., Schweppe, D. K., Rad, R., Erickson, B. K., ... Harper, J. W. (2017). Architecture of the human interactome defines protein communities and disease networks. *Nature, 545*(7655), 505–509. https://doi.org/10.1038/nature22366

Orchard, S., Ammari, M., Aranda, B., Breuza, L., Briganti, L., Broackes-Carter, F., Campbell, N. H., Chavali, G., Chen, C., del-Toro, N., Duesbury, M., Dumousseau, M., Galea, D., Hinz, U., Iannone, F., Jagannathan, S., Jimenez, R., Khadake, J., Lagreid, A., ... Hermjakob, H. (2014). The MIntAct project—IntAct as a common curation platform for 11 molecular interaction databases. *Nucleic Acids Research, 42*(D1), D358–D363. https://doi.org/10.1093/nar/gkt1115

Szklarczyk, D., Kirsch, R., Koutrouli, M., Nastou, K., Mehryary, F., Hachilif, R., Gable, A. L., Fang, T., Doncheva, N. T., Pyysalo, S., Bork, P., Jensen, L. J., & von Mering, C. (2023). The STRING database in 2023: Protein-protein association networks and functional enrichment analyses for any sequenced genome of interest. *Nucleic Acids Research, 51*(D1), D638–D646. https://doi.org/10.1093/nar/gkac1000

Stamatiades, G. A., Carroll, R. S., & Kaiser, U. B. (2019). GnRH—A key regulator of FSH. *Endocrinology, 160*(1), 57–67. https://doi.org/10.1210/en.2018-00889

Türei, D., Korcsmáros, T., & Saez-Rodriguez, J. (2016). OmniPath: Guidelines and gateway for literature-curated signaling pathway resources. *Nature Methods, 13*(12), 966–967. https://doi.org/10.1038/nmeth.4077

Uhlén, M., Fagerberg, L., Hallström, B. M., Lindskog, C., Oksvold, P., Mardinoglu, A., Sivertsson, Å., Kampf, C., Sjöstedt, E., Asplund, A., Olsson, I., Edlund, K., Lundberg, E., Navani, S., Szigyarto, C. A., Odeberg, J., Djureinovic, D., Takanen, J. O., Hober, S., ... Pontén, F. (2015). Tissue-based map of the human proteome. *Science, 347*(6220), Article 1260419. https://doi.org/10.1126/science.1260419

Human Protein Atlas. (n.d.). *GNRH1*. Retrieved October 9, 2026, from https://www.proteinatlas.org/ENSG00000147437-GNRH1

IntAct. (n.d.). *Molecular interaction database*. Retrieved October 9, 2026, from https://www.ebi.ac.uk/intact/

OmniPath. (n.d.). *OmniPath: Intra- and intercellular signaling knowledge*. Retrieved October 9, 2026, from https://omnipathdb.org/

STRING. (n.d.). *Protein association networks*. Retrieved October 9, 2026, from https://string-db.org/
