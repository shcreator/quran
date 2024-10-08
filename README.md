### Get The Entire Quran Text & Translations

This project is using the Uthmani Quran text from the [The Noble Qur'an Encyclopedia](https://quranenc.com/en/home). While the English transliteration is sourced from [Tanzil.net](https://tanzil.net/trans/en.transliteration). The translations are available in several languages:

- Quran text only: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran.json)
- Quran English transliteration: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_transliteration.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran.json)
- `bn` Bengali: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_bn.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_bn.json)
- `zh` Chinese: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_zh.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_zh.json)
- `en` English: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_en.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_en.json)
- `es` Spanish: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_es.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_es.json)
- `fr` French: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_fr.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_fr.json)
- `id` Indonesian: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_id.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_id.json)
- `ru` Russian: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_ru.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_ru.json)
- `sv` Swedish: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_sv.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_sv.json)
- `tr` Turkish: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_tr.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_tr.json)
- `ur` Urdu: [`cdn.jsdelivr.net/gh/shcreator/quran@master/quran_ur.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/quran_ur.json)

### Get the List of Chapters

- Arabic only: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/index.json)
- Bengali: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/bn/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/bn/index.json)
- Chinese: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/zh/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/zh/index.json)
- English: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/en/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/en/index.json)
- Spanish: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/es/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/es/index.json)
- French: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/fr/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/fr/index.json)
- Indonesian: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/id/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/id/index.json)
- Russian: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/ru/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/ru/index.json)
- Swedish: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/sv/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/sv/index.json)
- Turkish: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/tr/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/tr/index.json)
- Urdu: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/ur/index.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/ur/index.json)

### Get a Chapter

You can get a single chapter (surah) by providing its `chapterNumber` (`1-114`). Both Quran text and its transliteration are provided on each chapter. To get the translation you can also provide the `langCode`:

```
# Quran text & transliteration:
https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/{chapterNumber}.json

# Quran text, transliteration, and translation:
https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/{langCode}/{chapterNumber}.json
```

For example:

* *Al-Fatihah* Quran text only: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/1.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/1.json)
* *Al-Rahman* with English translation: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/en/55.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/en/55.json)
* *Al-Ikhlas* with Indonesian translation: [`cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/id/112.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/chapters/id/112.json)

### Get a Verse

You can get a single verse (ayah) by providing its `verseNumber` (`1-6236`).

```
https://cdn.jsdelivr.net/gh/shcreator/quran@master/verses/{verseNumber}.json
```

Unlike the rest of the JSON files, a single verse JSON file contains all available translations.

For example:

* *Al-Fatihah* verse #1: [`cdn.jsdelivr.net/gh/shcreator/quran@master/verses/1.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/verses/1.json)
* *An-Nas* verse #6: [`cdn.jsdelivr.net/gh/shcreator/quran@master/verses/6236.json`](https://cdn.jsdelivr.net/gh/shcreator/quran@master/verses/6236.json)

## Donate

DONATE US 🖤

BTC:(Bitcoin)

**ETH (Ethereum) ERC20** :  
0x0c201ed698c805927cc770faf223d556d6e1272b

**USDT(TRC20)**: 
TRRdzfnZtbwn9ecGSmXHN1wki92rECeN4X

**LTC (Litecoin):**  
LNV2uKdeQWfpVT3WHcPwTLhvqMoYGHyYX3`
