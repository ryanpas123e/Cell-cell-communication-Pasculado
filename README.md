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

** 1. What sender cell did you choose, and in what tissue or biological context does it act?

Hypothalamic GnRH neuron, acting in reproductive endocrine regulation by communicating with anterior pituitary gonadotroph cells.

** 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

Gonadotropin-releasing hormone (GnRH), encoded by GNRH1. The Human Protein Atlas (HPA) provides information associating GNRH1 with hypothalamic neuronal expression, supporting its selection as the candidate ligand.

** 3. What receptor receives the signal, and which receiver cell did you select?

GNRHR receives the signal. The receiver cell is an anterior pituitary gonadotroph, where GnRH signaling helps regulate LH and FSH synthesis and secretion.

** 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

Endocrine signaling, more specifically neuroendocrine signaling. GnRH travels from hypothalamic neurons to the anterior pituitary through the hypophyseal portal circulation.

** 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

GNAQ and GNA11 are relevant because their encoded G-protein alpha subunits are associated with Gq/11 signaling, which can activate PLCβ and downstream calcium signaling. GNAS is another G-protein-associated candidate in the network, but its presence alone does not establish its specific role in the selected pathway.

** 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The literature-supported mechanism is Gq/11–PLCβ signaling, involving IP3 production, calcium mobilization, DAG, and PKC activation. These processes contribute to the regulation of LH and FSH synthesis and secretion. I have not confirmed a specific enriched pathway, FDR, or enrichment p-value from my STRING results.

** 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct record EBI-21894414 reports a physical association between GNRHR and CAMK1D, detected by anti-tag coimmunoprecipitation in human HEK293T cells. The record is associated with Huttlin et al. (2017), PMID 28514442. This supports a reported physical association, but it does not establish direct binding or demonstrate the interaction in anterior pituitary gonadotrophs.

** 8. Which parts of your final model are strongly supported, and which parts remain an inference?

Strongly supported: The GNRH1–GNRHR ligand–receptor relationship reported by OmniPath and the GNRHR–CAMK1D physical association reported by IntAct. Supported by published literature: Gq/11–PLCβ signaling and its involvement in calcium mobilization and gonadotropin regulation. Inferred: The complete signaling sequence occurring in the selected sender–receiver cell pair and the resulting LH and FSH response, because the selected database results do not independently establish every step in those specific cells.

** 9. What cellular response is expected in the receiver cell, and why?

Regulation of luteinizing hormone (LH) and follicle-stimulating hormone (FSH) synthesis and secretion. GnRH binding to GNRHR activates intracellular signaling pathways that contribute to gonadotropin regulation, supporting reproductive endocrine function.
