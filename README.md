Втора лабораториска вежба по Софтверско инженерство<br>
<br>
Евгенија Николаевска, бр. на индекс: 193038<br>
<br>
Control Flow Graph<br>
<br>
![Slika](https://user-images.githubusercontent.com/82340818/120241803-d1107680-c263-11eb-9ad4-4c06e0c19c8e.png)<br>
1.Која е цикломатската комплексност на дадениот код? Објаснете како стигнавте до резултатот.<br>
-Цикломтската комплексност на дадениот код е 9 и таа е добиена со Цикломатската комплексност може да ја одкриеме преку бројот на региони или број на предикатни јазли.
 Предикатни јазли во нашиот код се:11; 12; 25; 18; 19; 13; 15. во нашиот случај бројот на предикатни јазли е 8, Р=8+1=9<br>
 <br>
2.Тест случаи според критериумот Every statement:Оваа метода налага да се генерираат test case-ови кои ќе овозможат тестирање на секоја наредба односно секој statement од кодот. A read hr,min,sec<br>
<br>
B type=''scalene''<br>
C if (hr < 0 || hr > 24)<br>
D type=''throw new RuntimeException("The hours are grater than E the maximum")''<br>
F if (min < 0 || min > 59)<br>
G type=''throw new RuntimeException("The minutes are not H valid!''<br>
I if (sec >= 0 && sec <= 59)<br>
J type='' result.add(hr * 3600 + min * 60 + sec)''<br>
ТЕСТ ПРИМЕРИ<br>
<br>
1,10,0<br>
2,20,1<br>
3hr,30min,2sec<br>
4hr,40min,3sec<br>
5hr,41min,4sec<br>
6hr,42min,5sec<br>
7hr,43min,6sec<br>
8hr,44min,7sec<br>
9hr,45min,8sec<br>
10hr,46min,9sec<br>
11hr,47min,10sec<br>
12hr,48min,11sec<br>
13hr,49min,12sec<br>
14hr,50min,13sec<br>
15hr,51min,14sec<br>
16hr,52min,15sec<br>
17hr,53min,20sec<br>
18hr,54min,30sec<br>
19hr,55min,40sec<br>
20hr,56min,50sec<br>
21hr,57min,55sec<br>
22hr,31min,58sec<br>
23hr,58min,59sec<br>
<br>
4.Тест случаи според критериумот Every path:претставува единствена секвенца од програмски јазли кои се извршуваат од даден test case.<br>
<br>
1,10,0<br>
2,20,1<br>
3hr,30min,2sec<br>
4hr,40min,3sec<br>
5hr,41min,4sec<br>
6hr,42min,5sec<br>
7hr,43min,6sec<br>
8hr,44min,7sec<br>
9hr,45min,8sec<br>
10hr,46min,9sec<br>
11hr,47min,10sec<br>
12hr,48min,11sec<br>
13hr,49min,12sec<br>
14hr,50min,13sec<br>
15hr,51min,14sec<br>
16hr,52min,15sec<br>
17hr,53min,20sec<br>
18hr,54min,30sec<br>
19hr,55min,40sec<br>
20hr,56min,50sec<br>
21hr,57min,55sec<br>
22hr,31min,58sec<br>
23hr,58min,59sec<br>
