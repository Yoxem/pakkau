### pakkau - a lomaji to hanji Taiwanese (Hokkien) converter

A test of Hidden Markov Model converter from lomaji to hanji of Taiwanese (Hokkien). still in alpha version.

## Dependencies
- Python3
- Pandas

## Help

usage: pakkau.py [-h] [--genmod] [--form FORM] [SENTENCE]

positional arguments:
  SENTENCE     the sentence to be converted

options:
  -h, --help   show this help message and exit
  --genmod     generate the model
  --form FORM  the orthography to be used (poj or tl). Default is poj. (not opened)

#### example1:
``
  python3 ./pakkau.py --form tl "Lāu-su kóng: \"ta̍k-ke tsò-hué lâi\""
``
output:

老師講："逐家做伙來"

#### example2:
``
python3 ./pakkau.py --genmod
``
generate models from the .csv parallel transliteration  file in ./corpus files


## unfinished
poj conversion
the preciseness of the conversion
