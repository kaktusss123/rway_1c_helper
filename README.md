<details>
    <summary> Телефон </summary>
    <p>
        
### Code

```
Если ТЕЛЕФОН.Количество() = 0 Тогда 
    Результат = "нет данных";
Иначе
    Результат = ТЕЛЕФОН;
КонецЕсли;
```

</p>
</details>

<details>
    <summary> Субъект </summary>
    <p>

### Regex

```
[Аа]дыг|[Аа]лтайск|[Аа]мурск|[Аа]рханг|[Аа]страх|[Бб]ашк|[Бб]елгор|[Бб]рянск|[Бб]урят|[Чч]еч|[Чч]еляб|[Чч]укот|[Чч]уваш|[Дд]агестан|[Ее]врейск|[Хх]абаров|[Хх]акас|[Хх]анты|[Ии]нгушет|[Ии]ркутс|[Ии]вановс|[Кк]абард|[Кк]алининг|[Кк]алмык|[Кк]алу|[Кк]амчатск|[Кк]арачаев|[Кк]арел|[Кк]емеров|[Кк]иров|[Кк]оми|[Кк]остромск|[Кк]раснодар|[Кк]расноярск|[Кк]урганс|[Кк]урск|[Лл]енингр|[Лл]ипецк|[Мм]агадан|[Мм]арий|[Мм]ордов|[Мм]осковск|[Мм]оскв|[Мм]урман|[Нн]енецк|[Нн]ижегор|[Нн]овгород|[Нн]овосибир|[Оо]мск|[Оо]ренбу|[Оо]рловс|[Пп]ензен|[Пп]ермск|[Пп]риморск|[Пп]сков|[Аа]лтай|[Кк]рым|[Рр]остовск|[Рр]язан|[Яя]кут|[Сс]ахалин|[Сс]амарск|[Сс]анкт|[Сс]аратов|[Оо]сети|[Сс]моленск|[Сс]тавропол|[Сс]вердлов|[Тт]амбов|[Тт]атарстан|[Тт]омск|[Тт]ул|[Тт]вер|[Тт]юмен|[Тт]ыва|[Уу]дмурт|[Уу]льян|[Вв]ладимир|[Вв]олгоград|[Вв]олог|[Вв]оронеж|[Яя]мал|[Яя]росл|[Зз]абайкал
```

### Code 

```
Если СтрНайти(СУБЪЕКТ, "Адыг") > 0 Тогда
    Результат = "Адыгея Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Алтайск") > 0 Тогда
    Результат = "Алтайский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Амурск") > 0 Тогда
    Результат = "Амурская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Арханг") > 0 Тогда
    Результат = "Архангельская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Астрах") > 0 Тогда
    Результат = "Астраханская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Башк") > 0 Тогда
    Результат = "Башкортостан Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Белгор") > 0 Тогда
    Результат = "Белгородская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Брянск") > 0 Тогда
    Результат = "Брянская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Бурят") > 0 Тогда
    Результат = "Бурятия Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Чеч") > 0 Тогда
    Результат = "Чеченская Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Челяб") > 0 Тогда
    Результат = "Челябинская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Чукот") > 0 Тогда
    Результат = "Чукотский АО";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Чуваш") > 0 Тогда
    Результат = "Чувашская Республика - Чувашия";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Дагестан") > 0 Тогда
    Результат = "Дагестан Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Еврейск") > 0 Тогда
    Результат = "Еврейская Аобл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Хабаров") > 0 Тогда
    Результат = "Хабаровский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Хакас") > 0 Тогда
    Результат = "Хакасия Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ханты") > 0 Тогда
    Результат = "Ханты-Мансийский Автономный округ - Югра АО";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ингушет") > 0 Тогда
    Результат = "Ингушетия Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Иркутс") > 0 Тогда
    Результат = "Иркутская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ивановс") > 0 Тогда
    Результат = "Ивановская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Кабард") > 0 Тогда
    Результат = "Кабардино-Балкарская Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Калининг") > 0 Тогда
    Результат = "Калининградская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Калмык") > 0 Тогда
    Результат = "Калмыкия Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Калу") > 0 Тогда
    Результат = "Калужская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Камчатск") > 0 Тогда
    Результат = "Камчатский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Карачаев") > 0 Тогда
    Результат = "Карачаево-Черкесская Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Карел") > 0 Тогда
    Результат = "Карелия Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Кемеров") > 0 Тогда
    Результат = "Кемеровская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Киров") > 0 Тогда
    Результат = "Кировская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Коми") > 0 Тогда
    Результат = "Коми Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Костромск") > 0 Тогда
    Результат = "Костромская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Краснодар") > 0 Тогда
    Результат = "Краснодарский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Красноярск") > 0 Тогда
    Результат = "Красноярский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Курганс") > 0 Тогда
    Результат = "Курганская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Курск") > 0 Тогда
    Результат = "Курская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ленингр") > 0 Тогда
    Результат = "Ленинградская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Липецк") > 0 Тогда
    Результат = "Липецкая обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Магадан") > 0 Тогда
    Результат = "Магаданская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Марий") > 0 Тогда
    Результат = "Марий Эл Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Мордов") > 0 Тогда
    Результат = "Мордовия Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Московск") > 0 Тогда
    Результат = "Московская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Москв") > 0 Тогда
    Результат = "Москва г";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Мурман") > 0 Тогда
    Результат = "Мурманская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ненецк") > 0 Тогда
    Результат = "Ненецкий АО";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Нижегор") > 0 Тогда
    Результат = "Нижегородская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Новгород") > 0 Тогда
    Результат = "Новгородская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Новосибир") > 0 Тогда
    Результат = "Новосибирская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Омск") > 0 Тогда
    Результат = "Омская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Оренбу") > 0 Тогда
    Результат = "Оренбургская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Орловс") > 0 Тогда
    Результат = "Орловская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Пензен") > 0 Тогда
    Результат = "Пензенская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Пермск") > 0 Тогда
    Результат = "Пермский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Приморск") > 0 Тогда
    Результат = "Приморский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Псков") > 0 Тогда
    Результат = "Псковская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Алтай") > 0 Тогда
    Результат = "Алтай Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Крым") > 0 Тогда
    Результат = "Крым Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ростовск") > 0 Тогда
    Результат = "Ростовская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Рязан") > 0 Тогда
    Результат = "Рязанская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Якут") > 0 Тогда
    Результат = "Саха /Якутия/ Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Сахалин") > 0 Тогда
    Результат = "Сахалинская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Самарск") > 0 Тогда
    Результат = "Самарская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Санкт") > 0 Тогда
    Результат = "Санкт-Петербург г";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Саратов") > 0 Тогда
    Результат = "Саратовская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Осети") > 0 Тогда
    Результат = "Северная Осетия - Алания Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Смоленск") > 0 Тогда
    Результат = "Смоленская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ставропол") > 0 Тогда
    Результат = "Ставропольский край";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Свердлов") > 0 Тогда
    Результат = "Свердловская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Тамбов") > 0 Тогда
    Результат = "Тамбовская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Татарстан") > 0 Тогда
    Результат = "Татарстан Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Томск") > 0 Тогда
    Результат = "Томская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Тул") > 0 Тогда
    Результат = "Тульская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Твер") > 0 Тогда
    Результат = "Тверская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Тюмен") > 0 Тогда
    Результат = "Тюменская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Тыва") > 0 Тогда
    Результат = "Тыва Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Удмурт") > 0 Тогда
    Результат = "Удмуртская Респ";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ульян") > 0 Тогда
    Результат = "Ульяновская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Владимир") > 0 Тогда
    Результат = "Владимирская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Волгоград") > 0 Тогда
    Результат = "Волгоградская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Волог") > 0 Тогда
    Результат = "Вологодская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Воронеж") > 0 Тогда
    Результат = "Воронежская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Ямал") > 0 Тогда
    Результат = "Ямало-Ненецкий АО";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Яросл") > 0 Тогда
    Результат = "Ярославская обл";
ИначеЕсли СтрНайти(СУБЪЕКТ, "Забайкал") > 0 Тогда
    Результат = "Забайкальский край";
КонецЕсли;
```
</p></details>