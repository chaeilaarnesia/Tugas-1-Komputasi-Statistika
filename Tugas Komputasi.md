# Tugas-1-Komputasi-Statistika
---
title: "TUGAS KOMPUTASI STATISTIKA 1"
author: "CHAEILA ARNESIA PURBA"
date: "2026-09-09"
output: html_document
---

#1. Vector numeric,Vector integer, Vector logical,Vector caracter
# Vector numeric
nilai <- c(60, 20, 80, 40)
print(nilai)
# Vector integer
angka <- c(5L, 2L, 3L, 1L)
print(angka)
# Vector logical
jawaban <- c(FALSE, TRUE, FALSE, TRUE)
print(jawaban)
# Vector character
nama <- c("ARNES", "OCA", "CIA", "NEY")
print(nama)

#2. matrix uk 4x4
tabel <- matrix(1:16, nrow = 4, ncol = 4)
tabel

#3. array 4d
susun <- array(1:16, dim = c(3, 2, 2, 2))
susun

#4. data frame kolom:4 (caracter, numeric, logical,logical,)
data_frame_4 <- data.frame(
  nama = c("ARNES", "OCA", "CIA", "NEY"),
  nilai = c(60, 20, 80, 40),
  logical1 = c(FALSE, TRUE, FALSE, TRUE),
  logical2 = c(TRUE, FALSE, TRUE, FALSE)
)
data_frame_4

#5. list 4 komponen: (vector numeric, vector integer, data frame, list)
#list isi 3 (vektor numeric, vektor integer, data frame))
isi <- list(
  c(60, 20, 80, 40),
  c(5L, 2L, 3L, 1L),
  data_frame <- data.frame(
  nama = c("ARNES", "OCA", "CIA", "NEY"),
  nilai = c(60, 20, 80, 40)
  ),
  list_utama <- list(
  vektor_numeric = c(60, 20, 80, 40),
  vektor_integer = c(5L, 2L, 3L, 1L),
  data_frame <- data.frame(
  nama = c("ARNES", "OCA", "CIA", "NEY"),
  nilai = c(60, 20, 80, 40)
)
)
)
print(isi)
