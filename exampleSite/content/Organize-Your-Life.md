---
title: Quick Guide to Bioinformatics for Horticulture Students
date: 2019-05-14T14:46:10.000+06:00
description: This is meta description
type: featured
image: ''
categories:
- project
tags:
- guide
- project

---

# Orientation and Future Perspective

At the end of September 2019, I challenged myself by joining a campaign named “[Iron man challenge: Continuous writing 30 days](https://ithelp.ithome.com.tw/2020ironman)“ hosted by “[ITHelp](https://ithelp.ithome.com.tw/)“, one of the biggest information technology communities in Taiwan, and generated the very first version of this quick guide in Chinese. There are many bioinformatics learning resources on the internet with technical details in English. In this quick guide, I intended to bypass the technical details, try to focus on the building of self-teaching habits, the value of academic integrity and growth mindset. Once the readers get an overview of what should be expected to learn, they should go on and acquire new knowledge from primary sources such as original research articles published by international academic journals. I plan to keep updating this quick guide as short term objective in terms of not only expanding and deepening the content but also turning it into multimedia tutorials. The long term goal is to make the learning environment and community more supportive and friendly for interdisciplinary learners.

This guide consists of four parts. I will elaborate on them one by one.

# 1. Introduction and minimal computer skill sets

   Assuming that readers have a biology/horticulture background, some computer utilization skills are required to start the journey into bioinfomatics. Just to list a few: familirity with unix-like environment and using command-line, text editor setting, running scripts (maybe R or Python).

   [RNA-Sick@Day1 > 你己被選中成為「賽博格研究生」｜生物資訊 の 冒險記趣 feat. Phylo](https://ithelp.ithome.com.tw/articles/10215861)

   [RNA-Sick@Day2 > 一旦接受了這種設定，操作起電腦還是挺帶感的嘛｜像個駭客一樣用電腦 feat. Terminal (終端機)](https://ithelp.ithome.com.tw/articles/10216613)

   [RNA-Sick@Day3 > 小孩子才要做選擇，我全都要｜入門生物資訊該學什麼語言呢 feat. Anaconda](https://ithelp.ithome.com.tw/articles/10217036)

   [RNA-Sick@Day4 > 我們凡事求一個圓｜第一次執行 Python 腳本就來算圓周率吧 feat. Jupyter Notebook](https://ithelp.ithome.com.tw/articles/10217180)

   [RNA-Sick@Day5 > 原來是純文字編輯器啊，我還以為是整合式開發環境呢｜準備一個喜歡的打字所在 feat. Atom](https://ithelp.ithome.com.tw/articles/10217983)

   [RNA-Sick@Day6 > 我相信自由自在，我詳細希望｜下載 NCBI 上的原始序列 feat. SRA Toolkit (上)](https://ithelp.ithome.com.tw/articles/10218654)

   [RNA-Sick@Day7 > 我相信自由自在，我詳細希望｜下載 NCBI 上的原始序列 feat. SRA Toolkit (下)](https://ithelp.ithome.com.tw/articles/10218998)

# 2. Transcriptome pipeline

   RNA-Sequencing (RNA-Seq) is one of the major game changing technologies in crop research. It is also the main reason for normal biology/horticulture students to further dive into bioinformatics. Although most of the sequencing service providers nowadays would generate a basic report containing figures and tables that can be directly used for publication, understanding the principles and algorithms is still a must for correct interpretation.

   [RNA-Sick@Day8 > Raw Data 是什麼，能吃嗎？｜ 一鍵了解序列品質 feat. FastQC](https://ithelp.ithome.com.tw/articles/10219591)

   [RNA-Sick@Day9 > 斷開序列，斷開一切的牽連｜把品質不佳的序列剔除掉 feat. Trimmomatic](https://ithelp.ithome.com.tw/articles/10219913)

   [RNA-Sick@Day10 > 我來組成頭部｜把短片段序列組裝成轉錄體 feat. Trinity](https://ithelp.ithome.com.tw/articles/10220238)

   [RNA-Sick@Day11 > 轉錄體補完計畫｜比對線上資料庫註解序列 feat. Trinotate](https://ithelp.ithome.com.tw/articles/10221160)

   [RNA-Sick@Day12 > 路遙知馬力，日久見人心｜用燕尾服套裝將序列比對到參考對象上 feat. Bowtie2](https://ithelp.ithome.com.tw/articles/10221594)

   [RNA-Sick@Day13 > 萬物皆虛，萬事皆允｜不用 alignment 推估表現量 feat. kallisto](https://ithelp.ithome.com.tw/articles/10222244)

   [RNA-Sick@Day14 > 檢定只是裝飾而已，上面的大人物是不會懂的｜篩選表現量有顯著差異的基因 feat. edgeR](https://ithelp.ithome.com.tw/articles/10222248)

   [RNA-Sick@Day15 > 銀河在呼喚我｜在網頁介面下完成轉錄體分析流程 feat. Galaxy](https://ithelp.ithome.com.tw/articles/10222720)

# 3. Comprehensive Analysis

   After acquiring differentially expressed genes from RNA-Seq, there are various ways to discover biological meanings from the data. Interesting results can be yielded by using heatmap to visualize transcript abundance, gene clustering according to expression pattern, or accessing online database using custom script.

   [RNA-Sick@Day16 > 基因代號進得去，生物意義出得來，GO 發大財｜基因本體論富集分析 feat. Gene Ontology (上)](https://ithelp.ithome.com.tw/articles/10223598)

   [RNA-Sick@Day17 > 基因代號進得去，生物意義出得來，GO 發大財｜基因本體論富集分析 feat. Panther classification system (中)](https://ithelp.ithome.com.tw/articles/10223846)

   [RNA-Sick@Day18 > 基因代號進得去，生物意義出得來，GO 發大財｜基因本體論富集分析 feat. REViGO (下)](https://ithelp.ithome.com.tw/articles/10224320)

   [RNA-Sick@Day19 > 快用你那無敵的非監督機器學習想想辦法吧｜依據表現量特徵將基因分群 feat. MAPMAN (上)](https://ithelp.ithome.com.tw/articles/10224724)

   [RNA-Sick@Day20 > 快用你那無敵的非監督機器學習想想辦法吧｜依據表現量特徵將基因分群 feat. K-means clustering (下)](https://ithelp.ithome.com.tw/articles/10224934)

   [RNA-Sick@Day21 > 是擅長畫 Pathway 的朋友啊｜用程式來查京都基因與基因體百科全書 feat. KEGG REST API](https://ithelp.ithome.com.tw/articles/10224942)

   [RNA-Sick@Day22 > 誰能阻止少年專題生呢？他們聽不到｜用程式上 NCBI 資料庫 feat. NCBI Entrez](https://ithelp.ithome.com.tw/articles/10225813)

   [RNA-Sick@Day23 > 基因調控什麼的最喜歡了｜啟動子區段序列之順式作用元件分析 feat. PLACE database](https://ithelp.ithome.com.tw/articles/10226253)

   [RNA-Sick@Day24 > 關於資料視覺化，我想說的是｜用 python 繪製充滿特色的圖表 feat. seaborn](https://ithelp.ithome.com.tw/articles/10226444)

   [RNA-Sick@Day25 > 我念 HMMER，但是我朋友都念 HMMER，聽說正解是HMMER｜基於隱藏式馬可夫鍊的超強序列比對軟體 feat. HMMER3](https://ithelp.ithome.com.tw/articles/10226897)

   [RNA-Sick@Day26 > 不被名稱耽誤的套裝軟體｜直接由序列內容預測功能區段 feat. MEME suite](https://ithelp.ithome.com.tw/articles/10227184)

# 4. Road to an Academic Career

   Besides the technical materials regarding data processing or sequence analysis, I included a part to talk about how to make use of digital tools to strengthen academic integrity and build personal brand as early-career researcher.

   [RNA-Sick@Day27 > 嘴巴說可以，身體卻一點也不老實啊｜程式碼筆記本保證研究可再現性 feat. NextJournal](https://ithelp.ithome.com.tw/articles/10227512)

   [RNA-Sick@Day28 > 今天的風兒 ...有點喧囂啊...｜架個個人網站來輔助你的學術海報呈現 feat. hexo on Github](https://ithelp.ithome.com.tw/articles/10227871)

   [RNA-Sick@Day29 > 我曾經都用 WORD，直到我膝蓋上中了一箭｜用 GTD 工作術加速論文撰寫 feat. Notion](https://ithelp.ithome.com.tw/articles/10228134)

   [RNA-Sick@Day30 > 生活就在呼吸之間｜不用寫程式做一個聊天機器人來檢索自己的三十天鐵人文章 (RNA-Sick 生物資訊小指南) feat. Chatfuel](https://ithelp.ithome.com.tw/articles/10228286)

---

# Here are some other awesome online resources and guidelines on the internet

[Path to a free self-taught education in Bioinformatics! by OSSU](https://www.facebook.com/rna.sick/posts/2490578204530555?__tn__=-R)

[My Journey Into Data Science and Bioinformatics — Part 1: Programming](https://towardsdatascience.com/my-journey-into-data-science-and-bio-informatics-749ece4d8860)



------

Last modified data: Jan 14 2020

Photo by [Alina Grubnyak](https://unsplash.com/@alinnnaaaa?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/network?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
