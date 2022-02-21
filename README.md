# hse_hw1_meth

### Ссылка на коллаб:
https://colab.research.google.com/drive/1fytVSJrqwTgmelxpVD7iG2aQfaMl1a6t?usp=sharing

## Part 1

BS-Seq | RNA
--- | --- 
<img width="490" alt="Screenshot 2022-02-18 at 00 53 20" src="https://user-images.githubusercontent.com/71605966/154577048-f144c6b7-8980-43b5-9db1-7b8833c6635c.png">  |  <img width="482" alt="Screenshot 2022-02-18 at 00 48 58" src="https://user-images.githubusercontent.com/71605966/154576438-c6146ed7-aaae-47e3-9ec1-ee18af7a6873.png">

Для RNA наблюдаем более высокий процент GC


### Per base sequence content
BS-Seq | RNA 
--- | --- 
<img width="830" alt="Screenshot 2022-02-18 at 00 53 54" src="https://user-images.githubusercontent.com/71605966/154577111-cc022d39-d2c6-4f7f-a0f7-2815f85036ae.png">  |  <img width="994" alt="Screenshot 2022-02-18 at 00 51 31" src="https://user-images.githubusercontent.com/71605966/154576793-9d88b250-006c-489b-b6b6-da3d6739892b.png">

Для BS-Seq наблюдаем выраженное отличие содержания TCAG, в отличие от RNA. Так, для BS-Seq почти отсутствуют Цитозины (C), cодержание Гуанина (G) ниже, а Тимина (T) – выше, чем в RNA


### Per sequence GC content

BS-Seq | RNA 
--- | --- 
<img width="816" alt="Screenshot 2022-02-18 at 00 52 12" src="https://user-images.githubusercontent.com/71605966/154576882-04e7ba01-8a60-4d1c-b34a-4e8fe015c0d5.png">  |  <img width="897" alt="Screenshot 2022-02-18 at 00 52 32" src="https://user-images.githubusercontent.com/71605966/154576941-2d8f20de-4600-4dc9-acdb-6a9d6c655ea5.png">

Для BS-Seq count per read заметно отличаются от теоритического распренедения: пиков два и они значительно выше


## Part 2

### Statistic

BS-Seq | 11347700-11367700 | 40185800-40195800 | deduplication
--- | --- | --- | ---
SRR5836473 | 1090 | 464 | 81.69
SRR5836475 | 1456 | 630 | 90.92
SRR3824222 | 2328 | 1062 | 97.08
