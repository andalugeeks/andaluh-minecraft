# Andaluh-minecraft

Transliterate español (spanish) minecraft JSON es_ES file to andaluz spelling proposals. Test this translation on Minecraft! We're releasing it under https://crowdin.com/project/minecraft/esan

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Support](#support)
- [Contributing](#contributing)

## Description

The **Andalusian varieties of [Spanish]** (Spanish: *andaluz*; Andalusian) are spoken in Andalusia, Ceuta, Melilla, and Gibraltar. They include perhaps the most distinct of the southern variants of peninsular Spanish, differing in many respects from northern varieties, and also from Standard Spanish. Further info: https://en.wikipedia.org/wiki/Andalusian_Spanish.

This application provides with a basic transliteration tool, using [andaluh-py](https://github.com/andalugeeks/andaluh-py) package. Further info: https://github.com/andalugeeks/andaluh-py

**PLEASE NOTICE** andalu-minecraft performs and automatic transliteartion from spanish to andaluz, hence all english, acronym or non spanish words will be wrongly transliterated. We encourage you to manually review all files transliterated.

The original es_ES.json file (minecraft spanish) can be downloaded from https://crowdin.com/project/minecraft
The result of this work is released under https://crowdin.com/project/minecraft/esan

## Usage

Use from the command line with the **andaluh-minecraft** tool:

```
$ andaluh-minecraft -h
Usage: andaluh-minecraft [options]

Options:
  -h, --help            show this help message and exit
  -i FILE_IN, --input=FILE_IN
                        Spanish JSON minecraft strings file.
  -o FILE_OUT, --output=FILE_OUT
                        File to save output. Prints to stdout if not included.

$ andaluh-minecraft ./es_ES.json ./es_AND.json
``` 

## Roadmap

* Migrating to python3

## Support

Please [open an issue](https://github.com/andalugeeks/andaluh-po/issues/new) for support.

## Contributing

Download Minecraft es_ES.json strings from https://crowdin.com/project/minecraft
Do you think there's anything wrong? Contribute with your andaluh transcriptions in https://crowdin.com/project/minecraft/esan

If you want to improve this repo code, please use [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and open a pull request.