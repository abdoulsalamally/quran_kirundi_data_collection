# quran_kirundi_data_collection
<img src="https://github.com/user-attachments/assets/34ea18f6-908f-4ac8-b3cf-9f962456ebb8" style="height:500px; width:200px"/>



This is a repository for the data collection of the Quran Kirundi Mobile app.


Above we have two files:
QuranAllContent.json (Entering data: Pasting the translation in) and The pdf file(The ready made Quran Kirundi to copy the translation from).

The QuranAllContent.json it's the one to be entering kirundi translation for each ayah.

For example:

          {
              "number": 790,
              "text": "ٱلْحَمْدُ لِلَّهِ ٱلَّذِى خَلَقَ ٱلسَّمَٰوَٰتِ وَٱلْأَرْضَ وَجَعَلَ ٱلظُّلُمَٰتِ وَٱلنُّورَ ۖ ثُمَّ ٱلَّذِينَ كَفَرُوا۟ بِرَبِّهِمْ يَعْدِلُونَ",
              "numberInSurah": 1,
              "juz": 7,
              "kirundi": "Ishimagizwa ni iry’Imana Allah[1], Yo Yaremye amajuru n’isi n’ibiri muri vyo; Irema n’umuco utuma haba ikurakuranwa ry’ijoro n’umurango. Hamwe n’ivyo biranga 
                         ubushobozi n’ububasha bw’Imana Allah, abagararije banganisha Imana Allah n’ibiremwa bakayibangikanya na vyo.", 
                         //Make sure it is one line otherwise it will show errors
              "page": 128,
              "ruku": 102,
              "hizbQuarter": 51,
              "sajda": false
            }

The "kirundi" field should be the one to be pasting the meaning for the ayah respectively from the pdf File.

Clone by using this url: https://github.com/abdoulsalamally/quran_kirundi_data_collection.git or download the zip file.
Pull and push to the origin (main).

Some github commands to use:
-git init
-git add .
-git commit -m "what you have done"
-git push -u origin main 

===============Please always push to the origin (main) whenever you have done translating.==========================

Jazakallahu khairan!!!!!


