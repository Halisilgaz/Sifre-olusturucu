
# Sifre-olusturucu
import random

karakterler = "+-/*!23456789&$#?=@<>abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

uzunluk = int(input("Lütfen şifre uzunluğunu giriniz : "))

sifre = ""

for i in range(uzunluk):
    sifre += random.choice(karakterler)


print("Oluşturulan Şİfreniz : ", sifre)
