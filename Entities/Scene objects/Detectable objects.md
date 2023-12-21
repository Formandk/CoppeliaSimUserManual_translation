# Об'єкти, здатні до виявлення

[Об'єкти](<Scene objects.md>), що здатні до виявлення, можуть бути "побаченими" [сенсорами наближення](https://www.coppeliarobotics.com/helpFiles/en/proximitySensors.htm). До цієї категорії належать:

- [Макети](https://www.coppeliarobotics.com/helpFiles/en/dummies.htm)
- [Форми](https://www.coppeliarobotics.com/helpFiles/en/shapes.htm)
- [Октодерева](https://www.coppeliarobotics.com/helpFiles/en/octrees.htm)
- [Хмари точок](https://www.coppeliarobotics.com/helpFiles/en/pointClouds.htm)

Зважаючи на те, що макети та хмари точок, власне, складаються з точок, вони не можуть бути виявлені сенсорами у формі променя чи рандомізованого пучка променів.

Подібні об'єкти можуть або виявлятися будь-якими сенсорами наближення, або лише дякими їх типами, або одною з наступних категорій сенсорів:
- Ультразвукові сенсори наближення
- Інфрачервоні сенсори наближення
- Лазерні сенсори наближення
- Індуктивні сенсори наближення
- Ємкісні сенсори наближення

[Колекції](../Collections.md) також вважаються здатними до виявлення, бо вони можуть містити об'єкти, що здатні до виявлення.

_Здатність до виявлень_ може бути точково активована або деактивована, що впливає на усі типи сенсорів наближення (для непримітивних форм вона активована зі створення). Ця властивість задається у [загальних властивостях об'єкта](<Properties/Object common properties.md>) або через [API](https://www.coppeliarobotics.com/helpFiles/en/apiFunctions.htm) функцію [`sim.setObjectSpecialProperty`](https://www.coppeliarobotics.com/helpFiles/en/regularApi/simSetObjectSpecialProperty.htm).

Окрім цього, _здатність об'єкта до виявлення_ може бути перевизначена через відповідні _параметри моделі_ (якщо він є складовою [моделі](<../../Scenes and models/Models.md>)). Для додаткової інформації дивіться [діалогове вікно налаштувань моделі](<../../Scenes and models/Models/Model dialog.md>).
