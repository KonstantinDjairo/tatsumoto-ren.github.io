---
title: Yomichan, EPWING and MDX dictionaries
date: 1607878153
tags: [dictionaries, yomichan, epwing]
---

In this article
I will provide you with download links for dictionary files.
These dictionary files can be opened with various programs,
including the ones mentioned below.
These files are almost indispensable for any language learner.
Having these files will help you to learn new words and get closer to fluency.
So, let's get started!

****

## EPWING

**EPWING** is a dictionary format
that was allegedly utilized in portable electronic dictionaries.
To view EPWINGs you need [Qolibri](setting-up-qolibri.html),
a dictionary viewer that lets you search multiple EPWING files at one time
so for every word you look up you immediately get multiple definitions.

Our community member, `Epistularum`,
made a collection of EPWING dictionaries.

<p align="center">
	<a class="download_button" href="https://nyaa.iss.ink/view/1577255">Download</a>
</p>

**Note:** you need a [torrent client](resources.html#torrent-clients) to download Torrent files.

<details>
<summary>Other sources</summary>

**Packs:**

* [EPWING Collection on Nyaa](https://nyaa.iss.one/view/1194089)
* [EPWINGs.rar on MediaFire](https://www.mediafire.com/file/hr30l1pw004gac9/EPWINGs.rar/file)
* [Mega](https://mega.nz/folder/UxhhlKzb#9T8-35RugwmkuZ33oTqVrQ)
* [by BritVSJapan](https://www.mediafire.com/folder/ldyklp3362pgg/Japanese_Dictionaries)

**Standalone dictionaries:**

* [NHK pitch accent dictionary EPWING](http://www.mediafire.com/file/sxmpse8n92c9oxg/NHKACT.zip).
A very useful EPWING with pitch accent information.
* [Shinmeikai EPWING with pitch accent](http://www.mediafire.com/file/q9b95d1ad9wnjxd/Shinmeikai.7z)
* [Kenkyusha J-E Dictionary](https://mega.nz/#F!dcoAlDSB!7ltFSsPmp1JfPhz6U5FaeQ)

</details>

## MDX

[GoldenDict](setting-up-goldendict.html)
is yet another dictionary lookup program that can be used for learning Japanese.
GoldenDict supports `MDX` dictionaries.
It can read `EPWING` dictionaries as well, but the feature is very clunky in my experience.
Qolibri is much better for EPWING.

`Epistularum` made a collection of MDX dictionaries for GoldenDict.

<p align="center">
	<a class="download_button" href="https://nyaa.iss.ink/view/1634529">Download</a>
</p>

**Note:** you need a [torrent client](resources.html#torrent-clients) to download Torrent files.

<details>
<summary>Other sources</summary>

* A collection of dictionaries is stored in [Freemdict Cloud](https://cloud.freemdict.com/index.php/s/pgKcDcbSDTCzXCs).
  It has a wider range of bilingual dictionaries.
* [A Dictionary of Japanese Grammar](https://forum.freemdict.com/t/topic/15854)

</details>

## Yomichan

Yomichan
is a web browser extension with a pop-up dictionary
that allows you to look up unknown words with the hover of a mouse.
To get Yomichan follow [this setup guide](setting-up-yomichan.html).
In order to be able to make Anki cards don't forget to install [AnkiConnect](https://ankiweb.net/shared/info/2055492159).

An archive with dictionaries for Yomichan can be downloaded by following the link below.

<p align="center">
	<a class="download_button" href="https://disk.yandex.com/d/dmS_-JVE2fkMDQ">Download</a>
</p>
<p align="center">
	<a href="https://t.me/ajatt_tools/115">Mirror</a>
</p>

<details>
<summary>Sources</summary>

The dictionaries were compiled from various places.
Below is a list of public folders that were used.

* [This Mega folder](https://mega.nz/folder/rIIHhAxb#d6GV9ZNTj9gUEaQtfGluqg)
* [Shared by mattvsjapan](https://www.mediafire.com/file/o3b6jt999dtd9vc/Yomichan_Dictionaries.zip/file)
* [Shinmeikai5](https://mega.nz/file/A5cRxIpY#fcCGZyWX6cZoFYwKoKzbdHnxm_S86WM3PSbDA4ifKUM)
* [Pitch Accent Dictionary](https://mega.nz/file/A5cRxIpY#fcCGZyWX6cZoFYwKoKzbdHnxm_S86WM3PSbDA4ifKUM)

</details>

Go to Yomichan settings and select the "Dictionaries" tab on the left side,
then click the button "Configure installed and enabled dictionaries…".
Press "Import" to import a new dictionary.

### About

Each folder in the archive contains a file called "README.md".
Open it to see additional information about the dictionaries.

### Don't import all Yomichan dictionaries

You need to have a lot of dictionaries at hand
because Japanese to Japanese dictionaries always have gaps in them.
There will always be words that are in some dictionaries and not in others.

**A few examples:**
* `夢海鼠` is only in `日本国語大辞典`.
* `禿同` is only in `実用日本語表現辞典`.

Though you might think that using every dictionary in Yomichan is a good idea
and load up all of them, I would advise you not to do so.
Sometimes the word that you're trying to look up
isn't the one that comes up first in the dictionary.
If you want to find it you have to scroll down,
and if you have many dictionaries imported this is going to be pretty annoying.

Each installed dictionary file causes Yomichan's database to expand significantly
and take up to several GiB of disk space.

So what I recommend you to do instead is to have as few dictionaries as possible
and use Qolibri whenever there's a word that you can't find in Yomichan.

### Custom CSS for images

If you want to use `デジタル大辞泉` or `旺文社国語辞典`,
images may render incorrectly unless you
append the following rules to your Popup CSS.
If this happens, go to Yomichan settings > "Appearance" > "Configure custom CSS...".

<details>
<summary>Popup CSS for images</summary>

```css
.gloss-image-description {
    text-align: center;
}

.definition-item-content,
.gloss-image-link {
    max-width: 100%;
}

.gloss-image-container {
    background: none !important;
}

.gloss-image-link[data-has-aspect-ratio="true"] .gloss-image {
    position: static;
    max-height: 200px;
}

.gloss-image-link[data-has-aspect-ratio="true"] .gloss-image-aspect-ratio-sizer {
    display: none;
}

.gloss-image-container-overlay {
    display: none;
}

img {
    will-change: transform;
}
```

</details>

### Custom CSS for Kanji Dictionaries

Yomichan's kanji dictionary viewer contains a lot of redundant information,
such as duplicated tags, stroke order diagrams and empty table rows for each entry.
To make the kanji entries more concise when using multiple kanji dictionaries,
you can add some CSS rules.

In "Settings" > "Popup Appearance" > "Configure custom CSS..."
paste the following CSS to condense displayed entries.

<details>
<summary>CSS for kanji</summary>

```css
/* remove misc dict classifications/codepoints/stats */
.kanji-glyph-data > tbody > tr:nth-child(n + 3) {
  display: none;
}

/* remove stroke diagram, freq, header for next entries */
div.entry[data-type='kanji']:nth-child(n + 2) .kanji-glyph-container,
div.entry[data-type='kanji']:nth-child(n + 2) [data-section-type='frequencies'],
div.entry[data-type='kanji']:nth-child(n + 2) table.kanji-glyph-data > tbody > tr:first-child {
  display: none;
}

/* remove 'No data found' */
.kanji-info-table-item-value-empty {
  display: none;
}

/* reduce extra padding */
.kanji-glyph-data,
div.entry[data-type='kanji'],
div.entry[data-type='kanji']:nth-child(n + 2) .kanji-glyph-data > tbody > tr > *,
.kanji-glyph-data dl.kanji-readings-japanese,
div.entry[data-type='kanji']:nth-child(n + 2)
  .kanji-glyph-data
  dl.kanji-readings-chinese[data-count='0'] {
  padding-top: 0 !important;
  padding-bottom: 0 !important;
  margin-bottom: 0em;
  margin-top: 0 !important;
}

/* remove horizontal lines */
.entry + .entry[data-type='kanji'],
div#dictionary-entries > div.entry:nth-child(n + 2) .kanji-glyph-data > tbody > tr > * {
  border-top: none !important;
}

/* change decimal list */
.kanji-gloss-list {
  list-style-type: circle;
}
```

</details>

## Explaining available dictionaries

### Bilingual

The goal of bilingual dictionaries is to provide you a rough tool
to help you get by until you switch to monolingual dictionaries.
On this stage JMdict is going to be enough for most people.
If you want to explore other available dictionaries, see the recommendations below.

I recommend you get the following dictionaries.

* [JMdict](https://www.edrdg.org/wiki/index.php/JMdict-EDICT_Dictionary_Project).
  The same dictionary that you find on
  [Jisho.org](https://jisho.org/).
  JMdict doesn't have example sentences.
  If you need them, try the resources listed
  [here](resources.html#examples-and-pronunciations).
* `新和英`.
  A dictionary made by Japanese people for Japanese people.
  We can learn Japanese words by using it in reverse.

For people who speak other languages.

* `研究社露和辞典`.
  A Russian-Japanese Dictionary.
  Russian speakers praise it a lot.
  Has example sentences.
* `Япон-Монгол толь бичиг`.
  A Japanese to Mongolian dictionary.

### Monolingual

Once you've started the monolingual transition, it is time to use real dictionaries.
`JMdict` is very limited and only contains simple translations, many of which can be misleading
because it's very rare for a word in one language to have an exact,
one-to-one correlate in another language.
Monolingual dictionaries, on the other hand, are very powerful because
they provide detailed definitions and usage examples.
With monolingual dictionaries you can learn your target language in your target language.

Pick 3 or 4 monolingual dictionaries you like the most and import them into Yomichan.
Don't be *that guy*, don't import all dictionaries at once.
Japanese to Japanese definitions are longer than Japanese to English ones.
It's easy to clutter Yomichan pop-ups with dozens of definitions.
Qolibri is much better than Yomichan at handling many dictionaries at the same time.

Some people may tell you that, say,
dictionary `A` has more precise and easy to read definitions than dictionary `B`.
In reality the differences between them are not very noticeable,
especially if you're someone who's already quite good at Japanese.
Almost all Japanese to Japanese dictionaries copy each other.
They change one or two words in the definitions here and there
to essentially avoid copyright strikes.
The provided example sentences are often the same word by word.
`新明解` is probably the only monolingual dictionary that offers original definitions,
but it's harder to follow because of how often it backtracks.

If you're new to monolingual dictionaries, it will take a few weeks to adjust to them.

**Most recommended:**

Below is a short list of dictionaries you see being recommended the most in the AJATT community.

* `大辞林`
* `新明解`
* `大辞泉`
* `明鏡`

Here I specify more or less generic names.
Often the same dictionary has many versions,
in which case the names can differ as well.
For example, `大辞林` and `スーパー大辞林`,
or `大辞泉` and `デジタル大辞泉`.
You're free to pick any version you like.

`大辞林` and `大辞泉` are quite similar to each other,
have good definitions and contain many entries.
Prefer `デジタル大辞泉` over the original `大辞泉`.
It has an extra 120 000 entries and contains images.
`明鏡` and `新明解` use easy language and are considered beginner-friendly.
`新明解` doesn't have many entries and has a convoluted definition structure
that employs a lot of redirections marked with `△` and `（）`
which force the reader to jump back and forth.
But mostly it's very good.
`大辞林` and `新明解` contain pitch accent information,
so you may want to import them first.

**Additional dictionaries:**

* 旺文社国語辞典.
A dictionary by Oubunsha.
Advertised as easy to understand for people new to monolingual dictionaries.
However, I've found that certain definitions use more difficult vocabulary than `大辞林`.
The file is big because it contains images.
There's a version without images called 旺文社国語辞典 第十一版 **画像無し**.
* Weblio古語辞典. Archaism dictionary from Weblio.
* 新辞林. You can treat it as a simplified version of `大辞林`.
* 日本国語大辞典. The biggest Japanese dictionary in the world.
  * 精選版 日本国語大辞典
  * 小学館 国語大辞典
* 岩波書店 岩波国語辞典
* 広辞苑
* 故事ことわざの辞典. Proverb dictionary.

### Frequency lists

Frequency lists are dictionaries
that display how frequently a word might appear in a given corpus.
They are utilized in Yomichan's headwords and are shown as tags.
Often frequency dictionaries have different frequency notations.
In some, a higher frequency number may indicate that the word is more frequent.
In others, it's the opposite.
You can use these dictionaries to judge
whether it is worth for you to learn a certain word or not.
Words that appear more frequently than others are more useful.

**Recommended:**

* Netflix frequency list
* Anime & Jdrama frequency list

These are a must-have if you watch dramas or anime a lot.

**Additional frequency lists:**

* Innocent corpus. Based on 5000+ novels.
* Narou. [Top 300 Narou stories](http://wiki.wareya.moe/Narou).
* VN. Visual Novels.
  I don't recommend VNs because most of them are proprietary,
  but the frequency list may help you detect common words in other types of content,
  for example manga and anime.
* BCCWJ &mdash; Based on [Long Unit Word list data](https://ccd.ninjal.ac.jp/bccwj/en/freq-list.html).
* Daijirin. Words that appear in the `大辞林` monolingual dictionary.
  You may want to take a look at it if you've decided to go monolingual,
  and you need to prioritize learning dictionary vocabulary.

### Grammar

Dictionaries for Yomichan that help you look up Japanese grammar.

* Nihongo no Sensei.
  Grammar by JLPT levels.
  The entries are in Japanese and Chinese.
  Has example sentences.
  The data comes from [nihongo no sensei](https://nihongonosensei.net).
* 日本語NET.
  Grammar by JLPT levels.
  The entries are in Japanese and English.
  Has example sentences with English translations.
  Data comes from [nihongokyoshi-net](https://nihongokyoshi-net.com/jlpt-grammars/).
* 日本語表現文型辞典.
  English explanations.
  Has examples sentences.
  Data comes from [donnatoki](https://djtguide.github.io/grammar/donnatoki).
* Dictionary of Japanese grammar.
  The entries are in English.
  Has example sentences.

### Pitch accent

Dictionaries for Yomichan capable of displaying pitch accents of words.
The default dictionary is [Kanjium](https://github.com/mifunetoshiro/kanjium).

### Kanji

In Yomichan Kanji dictionaries are shown
when you click on a kanji in the headword.

* [KanjiDic English](https://www.edrdg.org/wiki/index.php/KANJIDIC_Project).
  A Japanese-English kanji dictionary.
* `漢字源`.
  Monolingual kanji dictionary.
* [Wiktionary](https://ja.wiktionary.org/).
* NipDb Kanji. Kanji information of around 6,000 characters from NipDb.
* Kanji Map. Information about kanji.

### Other

* [JMnedict](https://www.edrdg.org/enamdict/enamdict_doc.html). Japanese names.
