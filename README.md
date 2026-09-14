# Zombie Harvest Loot

Мод для **7 Days to Die V3.2**: разделка **человеческих зомби ножом** (hunting knife, machete и любой инструмент с тегом butcher) даёт:

- гнилое мясо (`foodRottingFlesh`)
- жир (`resourceAnimalFat`)
- тряпки (`resourceCloth`)
- одежду с «крутых» / одетых зомби
- тематический лут профессии с шансом

Только XML, **DLL нет**. EAC можно оставить включённым, если у вас нет других DLL-модов.

Сделано в [Grok Build](https://grok.com).

---

## Требования

- 7 Days to Die **V3.2**
- Нож / мачете / другой butcher-инструмент для разделки трупа

## Установка (Windows)

1. Закройте игру.
2. Скачайте `ZombieHarvestLoot-1.1.0.zip` со страницы [Releases](https://github.com/daaag0n00969/7dtd-zombie-harvest-loot/releases/latest).
3. Распакуйте так:

```
%APPDATA%\7DaysToDie\Mods\ZombieHarvestLoot\ModInfo.xml
%APPDATA%\7DaysToDie\Mods\ZombieHarvestLoot\Config\entityclasses.xml
%APPDATA%\7DaysToDie\Mods\ZombieHarvestLoot\Config\loot.xml
```

Обычный путь:

```
C:\Users\<ИМЯ>\AppData\Roaming\7DaysToDie\Mods\ZombieHarvestLoot
```

4. Запустите игру. Работает на **уже существующем сейве**. Новый мир не нужен.

## Как пользоваться

1. Убейте зомби.
2. Возьмите **нож** (не дубину и не кирку).
3. Смотрите на **труп** и удерживайте кнопку добычи (обычно ЛКМ, как на животном).
4. Должна проиграться анимация разделки — с трупа падают мясо / жир / тряпки.

Редкие предметы профессии падают **не каждый раз**. Шанс сумки-лута при смерти слегка повышен (ваниль `0.04` → около `0.08`–`0.14` у профи-зомби).

## Таблица лута с разделки

| Зомби | Гарантия с ножа | Шанс дополнительно |
|---|---|---|
| Все человеческие зомби | Гнилое мясо, жир, тряпки | — |
| Медсестра | — | Бинты, обезболивающее, аптечка, антибиотики |
| Лаборант | — | Бинты, обезболивающее, витамины, аптечка |
| Хазмат | — | Бинты, обезболивающее, антибиотики |
| Рабочий (utility) | — | Молоток, гвозди, скотч, металлолом |
| Лесоруб | — | Топор, дерево, охотничий нож |
| Уборщик | — | Молоток, тряпки, скотч |
| Подрывник | — | Молоток, гвозди, металлолом |
| Ранчер | — | Нож, тряпки, лишнее мясо |
| Солдат | — | 9mm, 7.62, пистолет (редко), одежда T2 |
| Коп | — | 9mm, картечь, пистолет, самодельный дробовик (редко), одежда T2 |
| Байкер / боулер / бизнесмен / тусовщица / скейтбордист / зек / гавайский | — | Одежда T1 и/или доп. тряпки; у байкера ещё картечь, у бизнесмена старые купюры |

Feral / Radiated / Charged варианты **наследуют** разделку базового типа.

## Сумка при смерти

Ванильные пакеты `zPackNurse` / `zPackLab` / `zPackUtility` / `zPackSoldier` / `zPackThug` получают чуть больше тематических предметов. Копы используют солдатский контейнер (`EntityLootContainerSoldier`), чтобы в сумке чаще были патроны и оружие.

Это **не** гарантированный дроп с каждого трупа — сумка по-прежнему редкая.

## Удаление

Удалите `Mods\ZombieHarvestLoot`.

## Лицензия

MIT

---

# English

Harvest human zombies with a **knife / butcher tool** for rotting flesh, animal fat, cloth, extra clothing on dressed zombies, and low-chance job extras (meds, tools, guns/ammo).

XML-only. EAC can stay on if you use no other DLLs.

## Install

1. Close the game.
2. Download `ZombieHarvestLoot-1.1.0.zip` from [Releases](https://github.com/daaag0n00969/7dtd-zombie-harvest-loot/releases/latest).
3. Extract to `%APPDATA%\7DaysToDie\Mods\ZombieHarvestLoot\`
4. Start the game. Works on an existing save.

Use a blade with butcher harvest on the **corpse**. Loot-bag drop chance on the base template is raised (`0.04` → `0.08`), higher on job zombies.

## Changelog

- **1.1.0** — More professions (hazmat, demolition, rancher, inmate, businessman, party girl, skateboarder, hawaiian). Extra meds/tools/guns. Cop bags use soldier loot. Extra items in nurse/lab/utility/soldier/thug packs.
- **1.0.0** — First harvest table.

## License

MIT
