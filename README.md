# Proto-Germanic-Cognates
A dataset of Proto-Germanic cognates generated from Wiktionary data. Each entry is derived from the [Proto-Germanic lemmas](https://en.wiktionary.org/w/index.php?title=Category:Proto-Germanic_lemmas) category page on Wiktionary, with the corresponding cognates found by scraping the 'Descendants' section of each entry. 

There are two datasets over 8 languages (English, Dutch, German, Swedish, Danish, Icelandic, Gothic, Proto-Germanic):

* Orthographic Dataset: Includes the words as written in their modern language or using the reconstructed orthography for Proto-Germanic and (occasionally) Gothic.
* IPA Dataset: For modern languages the IPA is generated as in [Meloni, et al.](https://arxiv.org/pdf/1908.02477.pdf), using the [eSpeak](https://github.com/espeak-ng/espeak-ng/tree/master) library. For Gothic and Proto-Germanic, the IPA pronunciation is reconstructed according to the orthography. Stress markers are removed.

---

## Statistics

#### Number of Cognates per Entry

Most entries do not have a corresponding cognate in each of the 7 daughter languages. This data is compiled in the following table:

| Number of Daughter Cognates | Number of Entries |
| --------------------------- | ----------------- |
| 1                           | 906               |
| 2                           | 849               |
| 3                           | 772               |
| 4                           | 581               |
| 5                           | 451               |
| 6                           | 723               |
| 7                           | 454               |
| Total                       | 4736              |

#### Number of Entries per Language

| Language  | Number of Entries |
| --------- | ----------------- |
| English   | 2663              |
| Dutch     | 2508              |
| German    | 2717              |
| Swedish   | 2279              |
| Danish    | 1955              |
| Icelandic | 3232              |
| Gothic    | 1661              |

