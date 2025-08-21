# EmoTale
**A Danish and English emotional speech corpus**

Presented in the paper ["EmoTale: An Enacted Speech-emotion Dataset in Danish"](https://arxiv.org/abs/2508.14548) accepted to [ASRU 2025](https://2025.ieeeasru.org/).

General information
------------------------------------------------------------------

The EmoTale corpus contains Danish and English speech annotated affect states, and the data was collected as part of a master's thesis project at DTU. 
See more information in the datasheet: `EmoTale_datasheet.pdf`.

The data was collected in a quiet room at different locations using wireless RØDE microphones at a 48 kHz sampling rate. 
There are 18 speakers in the corpus (12 female and 6 male) with ages ranging between 9 and 39 years old.
EmoTale comprises a total of 800 utterances; 450 audio files in Danish and 350 files in English. 

The 5 emotions included in this dataset are: anger, happiness, sadness, boredom, and neutral.
Utterances in Danish and English are:
  | *No.*  | *Danish sentence*  | *English sentence* |
  | ------ | ------  | ------ |
  | 1. | _Dugen ligger på køleskabet._ | _The tablecloth is lying on the frigde._ |
  | 2. | _Det sorte ark papir er placeret deroppe ved siden af tømmerstykket._ | _The black sheet of paper is located up there besides the piece of timber._ |
  | 3. | _De bar det bare ovenpå og nu skal de ned igen._ | _They just carried it upstairs and now they are going down again._ |
  | 4. | _Det vil være på det sted, hvor vi altid opbevarer det._ | _It will be in the place where we always store it._ |
  | 5. | _Om syv timer er det morgen._ | _In seven hours it will be morning._ |


Filenames and speaker information
------------------------------------------------------------------
The audio files were named according to the same template, including information about the language, speaker ID, emotion, and sentence.
E.g., the file `DK_004_A_5.wav` contains the fifth sentence spoken by speaker 004 in Danish with an angry affect. 
Hence, categorical emotion labels can be extracted directly from the filename.
Information about gender and age can be found in the complementary `speaker_info.csv` file.

Annotations
------------------------------------------------------------------
In addition to the enacted emotion, two independent annotators provided four labels per instance: one categorical for the emotion chosen from the five possible classes, and three numerical for arousal, valence, and dominance in a range of 1 to 5 with increments of 0.5. These can be found in `annotations.csv`.

## Citation

```
@misc{hjuler2025_emotale,
      title={EmoTale: An Enacted Speech-emotion Dataset in Danish}, 
      author={Maja J. Hjuler and Harald V. Skat-Rørdam and Line H. Clemmensen and Sneha Das},
      year={2025},
      eprint={2508.14548},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2508.14548}, 
}
```

