---
title: "以tidyr和dplyr套件整理Google表單的複選題資料"
date: "2022-09-29"
tags:
- google表單
- 複選題
- R
- tidyr
- dplyr
categories:
- 資料整理
  
---

Google表單在題目為複選題時，會將填答者的回應全記錄在同一個欄位，不利後續分析。本文說明如何用R的tidyr和dplyr套件的函數來處理Google表單的複選題資料，以利做後續分析。

<!--more-->

Google表單在題目為複選題時，會將填答者的回應全記錄在同一個欄位，不利後續分析。本文說明如何用R的tidyr和dplyr套件的函數來處理Google表單的複選題資料，以利做後續分析。更簡單的作法是用splitstackshape套件來做，請見[此文](https://ccwupsy.github.io/2022/10/以splitstackshape套件整理google表單的複選題資料/)。

## 資料範例

請[點選此處](https://docs.google.com/spreadsheets/d/1Z9hGVdNaNmk41hbScOB1SUzTVZ_An41Z/edit?usp=sharing&ouid=102534642616283273245&rtpof=true&sd=true)下載google forms的資料範例。

資料為一虛擬的問卷資料，為25位大學生在五個問卷題目的回答。其中兩個題目是複選題，另有三個題目是四點量表的回答。

## 讀入資料



























