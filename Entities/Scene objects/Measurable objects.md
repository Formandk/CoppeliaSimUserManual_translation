# Об'єкти, здатні до вимірювання

Об'єкти, що мають цю властивість, можуть бути використані для [обчислення мінімальної відстані](https://www.coppeliarobotics.com/helpFiles/en/distanceCalculation.htm) з другими подібними об'єктами. До них відносяться:

- [Макети](https://www.coppeliarobotics.com/helpFiles/en/dummies.htm)
- [Форми](https://www.coppeliarobotics.com/helpFiles/en/shapes.htm)
- [Октодерева](https://www.coppeliarobotics.com/helpFiles/en/octrees.htm)
- [Хмари точок](https://www.coppeliarobotics.com/helpFiles/en/pointClouds.htm)

[Колекції](../Collections.md) також вважаються здатними до вимірювання, бо вони можуть містити об'єкти, що здатні до вимірювання.

Для подібних об'єктів _здатність до вимірювання_ може бути точково активована або деактивована (для таких об'єктів, як непримітивні форми, октодерева та хмари точок, вона активована зі створення). Ця властивість задається у [загальних властивостях об'єкта](<Properties/Object common properties.md>) або через [API](https://www.coppeliarobotics.com/helpFiles/en/apiFunctions.htm) функцію [`sim.setObjectSpecialProperty`](https://www.coppeliarobotics.com/helpFiles/en/regularApi/simSetObjectSpecialProperty.htm).

Окрім цього, _здатність об'єкта до вимірювання_ може бути перевизначена через відповідні параметри моделі (якщо він є складовою [моделі](<../../Scenes and models/Models.md>)). Для додаткової інформації дивіться [діалогове вікно налаштувань моделі](<../../Scenes and models/Models/Model dialog.md>).
