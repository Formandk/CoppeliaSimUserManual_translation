# Сцени та моделі

[Сцени](Scenes.md) та [моделі](Models.md) є основними складовими симуляції у CoppeliaSim. Модель це явно позначений піделемент на сцені. Сцена може містити будь-яку кількість моделей. Наступна картинка ілюструє відношення сцена-модель:

<p align="center">
<img src="sceneAndModel1.jpg" />
</p>
<p align="center">[Сцена і модель]</p>

І сцени і моделі можуть містити один чи кілька наступних елементів:
- [Об'єкти](<../Entities/Scene objects/Scene objects.md>)
- [Дочірні скрипти](https://www.coppeliarobotics.com/helpFiles/en/childScripts.htm)

На додачу до попердніх елементів сцена також буде містити наступне:
- [Середовище](../Environment/Environment.md)
- [Головний скрипт](https://www.coppeliarobotics.com/helpFiles/en/mainScript.htm)
- [Сторінки та види](<../User_Interface/Pages and views.md>)

Сцени зберігаються у `*.ttt`-файлах, а моделі - у `*.ttm`-файлах. Обидва типи можуть бути відкриті перетаскуванням їх з провідника на вікно з запущеною програмою CoppeliaSim. Також вони відкриваються подвійним настиканням.
