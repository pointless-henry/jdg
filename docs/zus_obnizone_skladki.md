# Переход на "Obniżone składki"

После 6 полных месяцев использования **Ulga na start** можно воспользоваться возможностью уплаты пониженных взносов ZUS (льгота "Obniżone składki", также известная как **Składki preferencyjne**) в течение 24 полных месяцев. Льгота заключается в том, что минимальные социальные взносы вычисляются на основе 30% минимальной заработной платы.

!!! success "Официальный сайт"
    [Obniżone składki ZUS przez 24 miesiące][19]

!!! question "Когда переходить на składki preferencyjne"
    См. [Сроки перехода между режимами][20]

## Что нужно сделать

Есть бухгалтер? Просто напомните ему о том, что у вас скоро заканчивается Ulga na Start.
Нет бухгалтера? Читайте инструкцию ⬇️

1. Сняться с учёта в ZUS с помощью бланка **ZUS ZWUA**.
2. Зарегистрироваться для страхования:

    a. Если работаете параллельно на Umowa o Pracę, то с помощью бланка **ZUS ZZA**;

    b. Иначе с помощью бланка **ZUS ZUA** с новым кодом 0570 xx. Если вы переходите с ulga na start на składki preferencyjne, то ваш старый код: **0540**, а новый: **0570**.

3. Переключить в настройках inFakt/wFirma/iFirma на składki preferencyjne.

Подробно и наглядно каждый из этих шагов описан ниже.

### 1. Снятие с учета (ZUS ZWUA)

#### Шаг 1

На странице **zus.pl** во вкладке **e-Płatnik** нужно выбрать новый документ типа **ZUS ZWUA**,
нажать *Wybierz* и в появившемся диалоге нажать *Przejdz do kreatora*.

![zus_obn_01][1]

Далее как *Cel obsługi* нужно выбрать пункт *Wyrejestrowanie ubezpieczonego*.

![zus_obn_02][2]

#### Шаг 2

Далее нужно указать причину и дату снятия с учета.

В поле *Przyczyna wyrejestrowania* нужно выбрать *600 - inna przyczyna wyrejestrowania*,
а в поле *Data wyrejestrowania* – первое число месяца. Остальные поля нужно оставить пустыми.

![zus_obn_03][3]

#### Шаг 3

Далее необходимо выбрать лицо, снимаемое с учета с *Kod tytułu ubezpieczenia* **054000** или **057000** и нажать *Dalej*.

#### Шаг 4

ZUS автоматически формирует комплект документов: создается не только ZWUA, но еще и ZCNA для выписки из реестра родственников, находящихся на содержании. Чтобы не пришлось добавлять их заново после регистрации, не отправляйте ZCNA в следующем шаге!

#### Шаг 5

Проверить, верифицировать и выслать документ ZWUA в ZUS.

#### Шаг 6

Если у вас есть родственники, находящиеся на содержании: перейдите в Dokumenty -> Dokumenty robocze, выделите ZCNA и удалите их при помощи кнопки Usuń.

### 2. Регистрация (ZUS ZUA) с кодом 05 70

Не спешите сразу после ZWUA отправлять заявку ZUA — пока ручная обработка первой заявки не завершена, ZUS не даст отправить вторую. Подождите, обычно это занимает 1-2 дня.

#### Шаг 1

На странице **zus.pl** во вкладке **e-Płatnik** нужно выбрать новый документ типа **ZUS ZUA**, нажать *Wybierz* и в появившемся диалоге нажать *Przejdz do kreatora*.

Далее как *Cel obsługi* нужно выбрать пункт *Zgłoszenie ubezpieczonego*.

![zus_obn_04][4]

#### Шаг 2

Заполнить *Dane identyfikacyjne* и *Dane ewidencyjne* в обоих вкладках. Можно загрузить уже имеющиеся в ZUS данные нажав
"Wybierz z kartoteki".

![zus_obn_05][5]

#### Шаг 3

Проверить *adres zameldowania*.

![zus_obn_06][6]

Проверить *adres zamieszkania*.

![zus_obn_07][7]

#### Шаг 4

Нажать *Dodaj kod tytułu ubezpieczenia*.

![zus_obn_8][8]

![zus_obn_81][81]

Выбрать *Kod tytułu ubezpieczenia*:

- Если вы переходите на składki preferencyjne - выбирайте код **05 70**.

*Data zgłoszenia do ubezpieczenia*: первое число месяца X. Важно, чтобы это был тот же день, что и для **ZUS ZWUA**. Тогда нет перерыва в страховании.

![zus_obn_12][12]

Выберите нужные пункты в секции *Obowiązkowe ubezpieczenia społeczne*.
Chorobowa складка (на больничные в случае болезни) - опциональна.
Можно снизить зус на 20+ злотых в месяц если отказаться от этой складки, но тогда вы не сможете получить
компенсацию больничных в случае болезни.

![zus_obn_82][82]

![zus_obn_83][83]

Выбрать *Kod wykonywanego zawodu*.

Например:

- **251401** Programista.
- **251402** Programista aplikacji mobilnych.
- **251903** Tester oprogramowania komputerowego.
- **243106** Specjalista do spraw marketingu i handlu.

Все коды можно найти по [ссылке][14].

_Если вы не меняли вид деятельности и просто хотите подать тот же код, который
использовали раньше, но забыли его, то можно посмотреть код в своей первичной
заявке ZZA на сайте **zus.pl**: открываете вкладку **e-Płatnik**, выбираете
**Dokumenty** и **Dokumenty w ZUS**, отмечаете в списке ZUS ZZA и нажимаете
**Podgląd**. В открытом документе ищите раздел
**V. TYTUŁ UBEZPIECZENIA I KOD WYKONYWANEGO ZAWODU** и смотрите пункт
**02. Kod wykonywanego zawodu**._

Нажать "Dodaj".

В появившимся диалоге нажать "ОК".

![zus_obn_11][11]

Выбрать только что созданного *ubezpieczonego* c кодом **057000**.

![zus_obn_10][10]

#### Шаг 5

Проверить, верифицировать и выслать документ в ZUS.

#### Шаг 6

Подождать, пока ZUS обработает заявку. Если всё ок, то должно быть вот так:

![zus_obn_84][84]

### 3. Переключение настроек сервиса для ведения бухгалтерии

!!! question "А очерёдность отправки деклараций имеет значение?"
    Не важно, в каком порядке совершать эти действия. Просто соблюдайте сроки.

!!! abstract "DRA"
    Оплата ZUS и отправка [ZUS DRA][15] с 1 по 20 число месяца, следующего за отчётным.

!!! abstract "ZWUA и ZUA/ZZA"
    ZUS ZWUA и ZUS ZUA/ZZA требуется отправить в ZUS с 1 по 7 число того месяца, в котором вы начали пользоваться льготой składki preferencyjne.

Изменять настройки в inFakt/iFirma/wFirma рекомендуется **после** того, как отправите перечисленные выше документы.

#### wFirma

Особое внимание очерёдности действий должны уделить пользователи wFirma.

wFirma после переключения в настройках на składki preferencyjne будет генерировать ZUS DRA как будто за предыдущий месяц у вас тоже были składki preferencyjne (без ulga na start). Из-за чего ZUS откажется принимать декларацию с неправильными кодом и суммой взносов (ошибка 69004101).

Поэтому лучше так:

1. сначала сгенерируйте ZUS DRA за предыдущий месяц (ваш последний DRA с ульгой на старт);
2. отправьте DRA в ZUS;
3. оплатите ZUS (этот шаг можно сделать и раньше и позже - не важно);
4. только после этого переключите ZUS в настройках wFirma на składki preferencyjne.

📚 Источник: [Koniec ulgi na start - przejście na preferencyjne składki ZUS](https://pomoc.wfirma.pl/-koniec-ulgi-na-start-przejscie-na-preferencyjne-skladki-zus)

!!! tip "Подсказка"
    Календарь wFirma подскажет вам, когда переключить настройки.
    ![календарь wFirma][16]

Ustawienia => Podatki => ZUS

Замените "Tylko zdrowotne — 6-miesięczna ulga na start" на "2-letni preferencyjny ZUS".
![2-letni preferencyjny ZUS][17]

**Исключение:** если вы ведёте предпринимательскую деятельность параллельно с работой по Umowa o Pracę (UoP), и ваша зарплата по UoP не ниже минимальной, то składki społeczne за вас платит работодатель. В этом случае вы освобождены от уплаты składki społeczne за себя как JDG — выбирайте "Tylko zdrowotne — 2-letni preferencyjny ZUS". Вы же подали ZUS ZZA на предыдущем этапе? То же самое касается и предпринимателей, которые получают пенсию.

![Tylko zdrowotne — 2-letni preferencyjny ZUS][18]

## UPP - подтверждение отправки

См. [UPP][21].

[1]: images/zus_obnizone/zus_obnizone_01.png
[2]: images/zus_obnizone/zus_obnizone_02.png
[3]: images/zus_obnizone/zus_obnizone_03.png
[4]: images/zus_obnizone/zus_obnizone_04.jpg
[5]: images/zus_obnizone/zus_obnizone_05.png
[6]: images/zus_obnizone/zus_obnizone_06.png
[7]: images/zus_obnizone/zus_obnizone_07.png
[8]: images/zus_obnizone/zus_obnizone_08.png
[81]: images/zus_obnizone/zus_obnizone_081.jpg
[82]: images/zus_obnizone/zus_obnizone_082.jpg
[83]: images/zus_obnizone/zus_obnizone_083.png
[84]: images/zus_obnizone/zus_obnizone_084.png
[9]: images/zus_obnizone/zus_obnizone_09.png
[10]: images/zus_obnizone/zus_obnizone_10.png
[11]: images/zus_obnizone/zus_obnizone_11.png
[12]: images/zus_obnizone/zus_obnizone_12.png
[13]: images/zus_obnizone/zus_obnizone_13.png
[14]: https://psz.praca.gov.pl/rynek-pracy/bazy-danych/klasyfikacja-zawodow-i-specjalnosci/wyszukiwarka-opisow-zawodow
[15]: declarations.md#zus-dra
[16]: images/zus_obnizone/wFirma_kalendarz.jpg
[17]: images/zus_obnizone/wFirma_schemat_2letni_preferencyjny_ZUS.jpg
[18]: images/zus_obnizone/wFirma_schemat_tylko_zdrowotne.jpg
[19]: https://www.biznes.gov.pl/pl/portal/00286
[20]: zus_next_level/#sroki-perekhoda-mezhdu-rezhimami
[21]: zus_next_level/#upp-podtverzhdenie-otpravki
