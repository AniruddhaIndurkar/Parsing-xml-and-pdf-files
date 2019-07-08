# Parsing xml and pdf files

## Parsing raw text files

Data-set that contains information about several units in the Monash University.
Each data-set contains information about the unit, e.g., unitcode, unit title, synopsis, requirements,
output, chief examiner, etc.
Task is to extract the data and transform the data into the XML and JSON format with the following
elements:
1. Unit code: is a 7-character string (three uppercase letter followed by 4 digits).
2. Pre-requisites: only the unit codes of the units that are pre-requisite + co-requisite for
the current unit (‘NA’ if the value is Null).
3. Prohibitions: only the unit codes of the units that are prohibited to be taken with the
current unit (‘NA’ if the value is Null).
4. Synopsis: a string containing the synopsis of the unit (‘NA’ if the value is Null)
5. Requirements: the list of requirements of the current unit (‘NA’ if the value is Null).
6. Outputs: the list of outputs of the current unit (‘NA’ if the value is Null).
7. Chief-examiners: the list of the chief-examiners of the current unit (‘TBA’ if Null).

## Text Pre-processing

Python code to preprocess a set of unit information and convert them into numerical representations (which are
suitable for input into recommender-systems/ information-retrieval algorithms).
