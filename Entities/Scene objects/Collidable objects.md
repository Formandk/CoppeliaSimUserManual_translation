# Об'єкти, здатні до стикання

[Об'єкти](<Scene objects.md>), що здатні до стикання, можуть брати участь у [виявленні зіткнень](https://www.coppeliarobotics.com/helpFiles/en/collisionDetection.htm) з іншими подібними об'єктами. Однак це не означає, що вони будуть [реагувати на зіткнення](https://www.coppeliarobotics.com/helpFiles/en/designingDynamicSimulations.htm#staticAndRespondable) – для цього є інша властивість. До об'єктів, здатних до стикання, належать:

- [Макети](https://www.coppeliarobotics.com/helpFiles/en/dummies.htm)
- [Форми](https://www.coppeliarobotics.com/helpFiles/en/shapes.htm)
- [Октодерева](https://www.coppeliarobotics.com/helpFiles/en/octrees.htm)
- [Хмари точок](https://www.coppeliarobotics.com/helpFiles/en/pointClouds.htm)

Зважаючи на те, що макети та хмари точок, власне, складаються з точок, вони можуть стикатися лише з октодеревами, які мають власний об'єм.

[Колекції](../Collections.md) також вважаються здатними до зіткнень, бо вони можуть містити об'єкти, що здатні до зіткнень.

Для подібних об'єктів здатність до зіткнень може бути точково активована або деактивована (для таких об'єктів, як непримітивні форми, октодерева та хмари точок, вона активована зі створення). Ця властивість задається у [загальних властивостях об'єкта](<Properties/Object common properties.md>) або через API функцію [`sim.setObjectSpecialProperty`](https://www.coppeliarobotics.com/helpFiles/en/regularApi/simSetObjectSpecialProperty.htm).

Окрім цього, здатність об'єкта до стикання може бути перевизначена через відповідні параметри моделі (якщо він є складовою [моделі](<../../Scenes and models/Models.md>)). Для додаткової інформації дивіться [діалогове вікно налаштувань моделі](<../../Scenes and models/Models/Model dialog.md>).
