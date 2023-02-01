# SynthV-FrenchDictionary
English to French, Chinese to French, Japanese to French & Multi-lingual to French .json dictionaries for [Synthesizer V](https://dreamtonics.com/en/synthesizerv/), based on the [French CMU Pronouncing Dictionary](https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/French/). It is converted from the [Open Utau French Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary), both are updated regularly.

You can learn more about French Synth and UTAUS on [utaufrance.com](https://utaufrance.com/) & if there's any issue, you can contact me through my [Twitter](https://twitter.com/mmem1m).

#### There may be wrong entries in the dictionary, please report them if so. This dictionary is by no means a plug and play solution and phoneme tweaking will still be required in order to make French Synthesizer V covers.

✨ Feel free to contribute or ask for words to be added. ✨

### Table of contents
- [How to download and install dictionaries on Windows]()
- [How to add a word]()
- [How to use the dictionary]()
- [Phoneme table]()
- [FAQ]()

### See Also
- [utaufrance.com](https://utaufrance.com/)
- [Word request thread](#)

## How to download and install dictionaries on Windows

If you just want to install the dictionary without contributing, you won't need a Github account or to understand how to use Git.
Just follow the two steps below : 

-  First, download the [CHN2FRA.json](#), [ENG2FRA.json](#), [JPN2FRA.json](#) or [ANY2FRA.json](#) file by clicking on the filename and then click on the download icon in the upper left corner of the file browser, as shown in the image below.

///

[Video tutorial on how to install dictionaries on Windows](https://www.youtube.com/watch?v=LI8hWO2PJGU)

-  Open SynthV and load the voice you want to use with the dictionary you downloaded. In the `Dictionary`panel, click on `New...` and then name the dictionary with the same name as the .json file (`CHN2FRA`, `ENG2FRA`, `JPN2FRA` or `ANY2FRA`). Make sure the language and phonemes match with your dictionary. The `ANY2FRA` dictionary can be used with any language or phonemes.

![CreateDictionary](https://i.imgur.com/XwpXmlU.png)

- You can now drag and drop the .json file in the `mandarin-xsampa` or `english-arpabet` folder in your Synthesizer V install, the path should be `Dreamtonics/Synthesizer V/dicts/language-alphabet`.

![DictionaryFolder](https://i.imgur.com/kHjXSCy.png)

- Reload Synthesizer V and you should now be able to select your dictionary.

## How to add a word

If you want to add a word to the dictionary, please add it to the [Open Utau Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary#how-to-add-a-word). You can also request words to be added in [issues](https://github.com/mmemim/OpenUTAU-French-Dictionary/issues).

## How to use the dictionary

You can type a word in French and split it in syllables with `+`. Because of the way Synth V handles syllables in Chinese, you'll have to add additional splits for CCs as shown below.

![WordSplitting](https://i.imgur.com/GC7yjcb.png)

If you want to say words like `l'année` or `j'en` you'll have to split them in two notes `l'` + `année` and `j'` + `en` as shown below.

![WordCombination](https://i.imgur.com/5K9zgrE.png)

In French, you also have [liaisons](https://en.wikipedia.org/wiki/Liaison_(French)), and some words might not always be pronounced the same way. Because of that, you may sometimes need to put `word(2)`, `word(3)` or even `word(4)`. For example, `absentes` has 4 entries.

![WordEntries](https://i.imgur.com/MsXgO0o.png)

## Phoneme table

Here is a table of the phonemes used for conversion in both dictionaries (in bold), additional phonemes are added.

| [IPA](https://en.wikipedia.org/wiki/Help:IPA/French) | Chinese X-SAMPA | English Arpabet | French Arpabet |
| ------------- | ------------- | ------------- | ------------- |
| a/ɑ : p**a**tte | a | ah | aa |
| e : cl**é** | e | **ih**/eh | ei |
| ɛ/ɛ: : b**ai**e | e | ae | ai |
| ə/ø : r**e**poser,  c**eu**x | 7/@ | uh | ee/eu |
| œ :  s**œu**r | **A**/@ | ax | oe |
| i : s**i** | i | **iy**/ih | ii |
| o : s**au**t | iU | ow | au |
| ɔ : p**o**mme | o | ao | oo |
| u : c**ou**p | u | uw | ou |
| y : r**u**e | y | **uh**/uw | uu |
| ɑ̃ : s**an**g, v**en**t | A N | aa ng | an |
| ɛ̃/œ̃ : v**in**, **un** | **7 n:**/7 N | ah ng | in/un |
| ɔ̃ : s**on** | o N | ao ng | on |
| b : **b**as | p | b | bb |
| d : **d**eux | t | d | dd |
| f : **f**aire | f | f | ff |
| g : **g**arçon | k | g | gg |
| k : **c**orps | kh | k | kk |
| l : **l**aisser | l | l | ll |
| m : **m**a | m | m | mm |
| ɲ : champa**gn**e | n j | n y | gn |
| ŋ : campi**ng** | N\:n | ng | unused |
| p : **p**ère | ph | p | pp |
| ʁ : **r**ega**r**der | x | hh | rr |
| s : **s**ans | s | s | ss |
| ʃ : **ch**ance | s` | sh | ch |
| t : **t**out | th | t | tt |
| v : **v**ous | f | v | vv |
| z : **z**éro | ts | z | zz |
| ʒ : **j**amais | ts` | zh | jj |
| j : pa**y**er | j | y | yy |
| w : **ou**i | w | w | ww |
| ɥ : h**ui**t | y | **uw**/uh | uy |

## FAQ

To be updated
