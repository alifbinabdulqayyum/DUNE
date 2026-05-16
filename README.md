# Introduction
This is the code repository of the paper: [Enhancing protein immunogenicity prediction via uncertainty weighted deep ensemble](https://doi.org/10.1093/oxfimm/iqag008)

# Installation Guide
Follow the installation guide from [VenusVaccine](https://github.com/ai4protein/VenusVaccine) repository.

# Train & Evaluate UQ Models
To train and evaluate the UQ models, follow the codes at [ImmUQBench](https://github.com/alifbinabdulqayyum/ImmUQBench) repository.

# Execute DUNE Method
To execute the DUNE methodology, we first train different UQ models with different PLMs. The results are stored in the attached files `Virus-Virus.pkl`, `Bacteria-Bacteria.pkl` and `Tumor-Tumor.pkl` for the ImmunoDB dataset of the [VenusVaccine](https://github.com/ai4protein/VenusVaccine) repository.

Run the `DUNE_Method.ipynb` file to execute the DUNE method with evaluations with different UQ models.

# Citation
```
@article{10.1093/oxfimm/iqag008,
    author = {Qayyum, Alif Bin Abdul and Rahmati, Amir Hossein and Qian, Xiaoning and Yoon, Byung-Jun},
    title = {Enhancing protein immunogenicity prediction via uncertainty weighted deep ensemble},
    journal = {Oxford Open Immunology},
    volume = {7},
    number = {1},
    pages = {iqag008},
    year = {2026},
    month = {01},
    issn = {2633-6960},
    doi = {10.1093/oxfimm/iqag008},
    url = {https://doi.org/10.1093/oxfimm/iqag008},
    eprint = {https://academic.oup.com/ooim/article-pdf/7/1/iqag008/68284741/iqag008.pdf},
}
```