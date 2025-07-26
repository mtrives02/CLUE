# CLUE (Conventional Language Units for Evaluation)
Author: Marta Ramírez Trives

## Download Link
[Click here to download the full version of the CLUE dataset](https://github.com/mtrives02/CLUE/releases/download/1.0/clue_dataset.zip)

## Description
CLUE is a Spanish-English pararell dataset for training and evaluating LLMs in figurative language processing. It is based on the Conventional Figurative Language Theory (CFLT) and is composed of one-word metaphors, idioms, similes, and proverbs.

CLUE's bilingual nature allows for a direct comparative evaluation of performance in English versus Spanish, a language with comparatively fewer resources in the field of AI.
The dataset can be used in multiple figurative language processing tasks, such as detection, interpretation, and generation.

The CLUE dataset was developed within the framework of the Master's thesis "El lenguaje figurado en los LLM: evaluación y análisis" (Figurative Language in LLMs: Evaluation
and Analysis) at the University of Alicante. The thesis provides a detailed description of CLUE's creation and a comprehensive evaluation of the performance of several
state-of-the-art language models.

## Contents
### Files
* [clue_en.csv](https://github.com/mtrives02/CLUE/blob/main/clue_en.csv) - the dataset in English.
* [clue_es.csv](https://github.com/mtrives02/CLUE/blob/main/clue_es.csv) - the dataset in Spanish.
### Data Fields
* CFU - the Conventional Figurative Unit (e.g., "to kick the bucket").
* Type - the type of CFU (simplex, idiom, simile, proverb).
* Concept - the basic meaning of concept expressed by the CFU (e.g., "to die").
* Context - a real example sentence showing the use of the CFU.

## Citing
If you use this dataset in your work, please cite the following Master's thesis:
```
@mastersthesis{ramireztrives2025lengfig,
  title={El lenguaje figurado en los {LLM}: evaluaci{\'o}n y an{\'a}lisis},
  author={Ram{\'i}rez Trives, Marta},
  school={University of Alicante},
  address={San Vicente del Raspeig, Espa{\~n}a}
  type={Master's thesis}
  year={2025},
}
```

## License
Distributed under the [Creative Commons Zero v1.0 Universal license](https://github.com/mtrives02/CLUE/blob/main/LICENSE).

## Acknowledgements
This research work is part of the R&D project "CORTEX: Conscious Text Generation" (PID2021-123956OB-I00), funded by MCIN/AEI/10.13039/501100011033 and the ERDF "A way of
making Europe."
