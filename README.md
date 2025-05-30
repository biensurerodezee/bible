# Bible API on GitHub 🇸🇦 🇨🇳 🇩🇪 🇬🇷 🇺🇸 🇬🇧 🇺🇳 🇪🇸 🇫🇮 🇫🇷 🇰🇷 🇧🇷 🇵🇹 🇷🇴 🇷🇺 🇻🇳

## Description

This repository provides a simple API to access verses from the Bible directly from GitHub. The verses are available in JSON format.


# Endpoints

## By Language and Bible Books

To access specific books within a Bible version, use this endpoint:

```
https://raw.githubusercontent.com/biensurerodezee/bible/main/{language}/{book-id}/{book-id}.json
```

### Try:

```sh
curl https://raw.githubusercontent.com/biensurerodezee/bible/main/en/gn/gn.json
```

## By Language, Bible, Chapter and Verse

To access specific chapters and verses within a book, use the following endpoint:

```
https://raw.githubusercontent.com/biensurerodezee/bible/main/{language}/{book-id}/{chapter}/{verse}.json
```

### Try:

```sh
curl https://raw.githubusercontent.com/biensurerodezee/bible/main/en/2ch/2/1.json
```


## Languages and Versions

The summary endpoint provides an overview of available languages and versions. For detailed information, refer to the specific endpoints provided above.

### Arabic 🇸🇦

| Language ID | Version Name     | Version ID |
| ----------- | ---------------- | ---------- |
| ar          | The Arabic Bible | svd        |

### Chinese 🇨🇳

| Language ID | Version Name          | Version ID |
| ----------- | --------------------- | ---------- |
| zh          | New Chinese Version   | ncv        |

### German 🇩🇪

| Language ID | Version Name | Version ID |
| ----------- | ------------ | ---------- |
| de          | Schlachter   | schlachter |

### Greek 🇬🇷

| Language ID | Version Name | Version ID |
| ----------- | ------------ | ---------- |
| el          | Modern Greek | greek      |

### English 🇺🇸🇬🇧

| Language ID | Version Name       | Version ID |
| ----------- | ------------------ | ---------- |
| en          | King James Version | kjv        |

### Esperanto 🇺🇳

| Language ID | Version Name | Version ID |
| ----------- | ------------ | ---------- |
| eo          | Esperanto    | esperanto  |

### Spanish 🇪🇸

| Language ID | Version Name | Version ID |
| ----------- | ------------ | ---------- |
| es          | Reina Valera | rvr        |

### Finnish 🇫🇮

| Language ID | Version Name  | Version ID |
| ----------- | ------------- | ---------- |
| fi          | Finnish Bible | finnish    |

### French 🇫🇷

| Language ID | Version Name       | Version ID |
| ----------- | ------------------ | ---------- |
| fr          | Le Bible de I'Épée | apee       |

### Korean 🇰🇷

| Language ID | Version Name   | Version ID |
| ----------- | -------------- | ---------- |
| ko          | Korean Version | ko         |

### Portuguese 🇵🇹

| Language ID | Version Name                      | Version ID |
| ----------- | --------------------------------- | ---------- |
| pt          | Nova Versão Internacional         | nvi        |

### Brazil 🇧🇷

| Language ID | Version Name                      | Version ID |
| ----------- | --------------------------------- | ---------- |
| br          | Almeida Corrigida e Revisada Fiel | acf        |


### Romanian 🇷🇴

| Language ID | Version Name                 | Version ID |
| ----------- | ---------------------------- | ---------- |
| ro          | Versiunea Dumitru Cornilescu | cornilescu |

### Russian 🇷🇺

| Language ID | Version Name        | Version ID |
| ----------- | ------------------- | ---------- |
| ru          | Синодальный перевод | synodal    |

### Vietnamese 🇻🇳

| Language ID | Version Name | Version ID |
| ----------- | ------------ | ---------- |
| vi          | Tiếng Việt   | vietnamese |

# Book IDs

The table below lists the IDs and names of the books available in the API:

| ID   | Name            |
| ---- | --------------- |
| gn   | Genesis         |
| ex   | Exodus          |
| lv   | Leviticus       |
| nm   | Numbers         |
| dt   | Deuteronomy     |
| js   | Joshua          |
| jud  | Judges          |
| rt   | Ruth            |
| 1sm  | 1 Samuel        |
| 2sm  | 2 Samuel        |
| 1kgs | 1 Kings         |
| 2kgs | 2 Kings         |
| 1ch  | 1 Chronicles    |
| 2ch  | 2 Chronicles    |
| ezr  | Ezra            |
| ne   | Nehemiah        |
| et   | Esther          |
| job  | Job             |
| ps   | Psalms          |
| prv  | Proverbs        |
| ec   | Ecclesiastes    |
| so   | Song of Solomon |
| is   | Isaiah          |
| jr   | Jeremiah        |
| lm   | Lamentations    |
| ez   | Ezekiel         |
| dn   | Daniel          |
| ho   | Hosea           |
| jl   | Joel            |
| am   | Amos            |
| ob   | Obadiah         |
| jn   | Jonah           |
| mi   | Micah           |
| na   | Nahum           |
| hk   | Habakkuk        |
| zp   | Zephaniah       |
| hg   | Haggai          |
| zc   | Zechariah       |
| ml   | Malachi         |
| mt   | Matthew         |
| mk   | Mark            |
| lk   | Luke            |
| jo   | John            |
| act  | Acts            |
| rm   | Romans          |
| 1co  | 1 Corinthians   |
| 2co  | 2 Corinthians   |
| gl   | Galatians       |
| eph  | Ephesians       |
| ph   | Philippians     |
| cl   | Colossians      |
| 1ts  | 1 Thessalonians |
| 2ts  | 2 Thessalonians |
| 1tm  | 1 Timothy       |
| 2tm  | 2 Timothy       |
| tt   | Titus           |
| phm  | Philemon        |
| hb   | Hebrews         |
| jm   | James           |
| 1pe  | 1 Peter         |
| 2pe  | 2 Peter         |
| 1jo  | 1 John          |
| 2jo  | 2 John          |
| 3jo  | 3 John          |
| jd   | Jude            |
| re   | Revelation      |

# Formatting

```sh
npx prettier --write .
```

## Contributing

This repository is open to contributions. Feel free to propose improvements or add new features. To contribute, please submit a pull request with your changes.

If you encounter any issues or have suggestions, please open an issue to discuss.

## License

This project is distributed under the [MIT](LICENSE) license.
