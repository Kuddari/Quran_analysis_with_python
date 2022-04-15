# Quran-Database-and-Data-Warehouse

# Overview
This repository contains all data that is related with Al-Quran, from the Ayah(Text and translation), Tafsir(explanation) ,surah and word by word. It's collected from open sources and stored as file.csv and JSON to make it easy to use in various programming language.In this section, we have analyzed the data using the star schema design method for efficient data analysis and bring it into the process of programming to make it easier to run.

# Tools of use
- A Computer
- Python => 3
- Jupyter, IPython 
- Visual Studio Code
- PostgreSQL
- Git, GitHub, GitHub Desktop

# Al-Quran Dataset
There are 6 translations which taken from several open sources.
- Chinese_translate.csv= Chinese Language
- cambodia_translate.csv=Cambodian Language
- en_translate.csv=English Language
- id_translate.csv=Indonesian Language
- malay_translate.csv=Malay Language
- thai_translate.csv=Thai Language
 
There are two Languages of Surah
- en_surah.csv =English
- id_surah.csv=Indonesian

There are three Languages of Tafsir
- ar-mukhtasar-islamhouse.md=Arabic
- en-mukhtasar-islamhouse.md=English
- id-mukhtasar-islamhouse.md=Indonesian

There are three language of Word by word
- Word.csv= Arabic
- en_word.csv=English
- id_word.csv=Indonesian

# Step to do star schema and analysis
- Download PostgreSQL
- Create the  database and fill it with data
- Insert the dataset
- Create Fact Table
- Choose Arabic_word as Fact Table  
- Connect Fact Table to all dimension Table including Surah Ayah Translate
- For Analysis you can see how to do  via this link https://github.com/Kuddari/QuranTranslater/blob/main/quran_analysis.ipynb

Question&answer
- 1.What is the longest surah in Quran and how many words are there?
  Ans: Al-Baqara and have 6116 words
- 2.What is the shortest surah is Quran?
  Ans: Al-Kawthar and have 10 words
- 3.What is the longest ayah in Quran?
  Ans: Al-Baqara
- 4.How many words in Quran?
  Ans: There are 77429 words in quran.
- 5.Which ayahs are have only one word?
  Ans:
  surah  ayah   words	text
0	آل عمران	1	1	الٓمٓ
1	الأحقاف	1	1	حمٓ
2	الأعراف	1	1	الٓمٓصٓ
3	البقرة	1	1	الٓمٓ
4	الجاثية	1	1	حمٓ
...	...	...	...	...
23	غافر	1	1	حمٓ
24	فصلت	1	1	حمٓ
25	لقمان	1	1	الٓمٓ
26	مريم	1	1	كٓهيعٓصٓ
27	يس	1	1	يسٓ
- 6.How many different types of words in Quran?
  Ans: There are 25457 types of words in quran
- 7.How many اللّٰهُ words in Quran?
  Ans:2689 words, 3.47% of words in Quran
- 8.How many times Quran mentions about Allah according to english translation?
  Ans: 3137 words
- 9.What are the most starting words in quran?
  Ans: اِنَّ , قَالَ , قُلْ
- 10.What are the most frequently used words in Quran?
  Ans: مِنْ , الَّذِیْنَ , مَا
- 11.How many words that revelation in Mekkah and How many words in Madinah?
  Ans:	medinan	29990 =	38.732258%
	meccan	47439 =	61.267742%
- 12.How many ayah that revelation in Mekkah and How many Ayahs in Madinah?
  Ans: 	medinan	1623 =	26.026299%
	meccan	4613 =	73.973701%
	
# Data source
hablullah, A. (2021) data-quran.: Live Science [online]. Available at: https://github.com/hablullah/data-quran [Accessed 8-15th April 2022].

# Authors
- Kyaw Swar Win
- Abdulhaiyee Sani
- Sananpong Insuwan

# Conclusion
In conclusion, this repository has discussed four key area is information about the Quran
Al-Quran Dataset,Tools of use,Step to do star schema and analysis and saw that dealing with 
the Quran database can be a sentence for people who are very interested.
