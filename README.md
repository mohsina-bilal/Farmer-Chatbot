# Government Schemes Dataset (English–Hindi)

This repository contains the processed bilingual dataset developed as part of the research work submitted for publication. The dataset focuses on **government schemes for farmers in India** and is provided here as supplementary material to support reproducibility, transparency, and further exploration by the research community.

## 📂 Repository Contents
- **`scheme_details en - english schemes.csv`**  
  Contains curated scheme details in English.

- **`scheme_details hi - hindi schemes.csv`**  
  Contains the same scheme details translated and normalized into Hindi.

- **`scheme_details enhi - EN-HI schemes.csv`**  
  A bilingual alignment of English and Hindi scheme details for parallel processing and evaluation.

- **`machine_translation_dataset.json`**  
  JSON-formatted dataset created for machine translation experiments, containing scheme-level pairs in English and Hindi.

- **`.gitignore`, `LICENSE`, `README.md`**  
  Standard repository files.

## 🧾 Dataset Description
The dataset has been curated from **official government portals** and includes key details such as:
- Scheme name  
- Eligibility criteria  
- Required documents  
- Benefits and descriptions  

Data has been **pre-processed and normalized** to ensure consistency across languages. Hindi translations were generated using a **hybrid approach**, combining automated machine translation with manual cleaning for accuracy.

## Purpose
This dataset is released to:
1. Provide a **bilingual resource** (English–Hindi) for research in **low-resource NLP**, machine translation, and retrieval-augmented generation (RAG).  
2. Support **chatbot development** for farmers in India, enabling access to agricultural government schemes in regional languages.  
3. Serve as **supplementary information** to the associated research paper submission.

## Citation
If you use this dataset, please cite the associated research paper (currently under submission). Citation details will be updated once available.

## License
This dataset is released under the **MIT License**, permitting reuse with attribution.

## Future Work
- Expansion of the dataset to cover additional regional Indian languages.  
- Integration of multimodal resources (speech and scanned documents).  
- Continuous updates in alignment with ongoing research.
