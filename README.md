# Nuclear Option — Беларускі патч (Localization Patch)

Мод беларускай лакалізацыі для Nuclear Option. Працуе як плагін BepInEx і перакладае інтэрфейс, энцыклапедыю, падказкі і ўсплывальныя апісанні.

## Патрабаванні

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Ранні доступ 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Усталёўка

1. Усталюйце **BepInEx 5.x** у папку гульні.
   ```
   Прыклад: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Запусціце гульню **адзін раз** і зачыніце яе. (Гэта створыць структуру папак BepInEx.)

3. Скапіруйце ўсе файлы з гэтага рэпазіторыя ў:
   ```
   [Папка гульні]\BepInEx\plugins\LocalizationPatch\
   ```
   > Калі папкі «LocalizationPatch» няма, стварыце яе ўручную.

4. Запусціце гульню — **беларускі пераклад прымяніцца аўтаматычна**.

### Аўтаматычны ўсталёўшчык (альтэрнатыва)

https://github.com/9138noms/NuclearOption-LocalizationInstaller/releases/latest

## Уключаныя файлы

| Файл | Апісанне |
|------|----------|
| `LocalizationPatch.dll` | Плагін перакладу |
| `blr.json` | Дадзеныя беларускага перакладу |
| `Exo2-Regular.ttf` | Шрыфт для адлюстравання тэксту |

## Гарачыя клавішы ў гульні

| Клавіша | Функцыя |
|---------|---------|
| `F10` | Паказаць/схаваць аверлей адладкі |
| `Ctrl+F10` | Перазагрузіць дадзеныя перакладу (гарачая перазагрузка) |

## Заўвагі

- Назвы фракцый (PALA, BDF, BOSCALI, PRIMEVA, FFL, LMA) і кодавыя імёны тэхнікі / зброі (Compass, Alkyon AB-4, FGA-57 Anvil, IRM-S2 і г.д.) застаюцца на англійскай.
- У выпадку праблем мову можна паказаць уручную ў файле `BepInEx\config\com.noms.localizationpatch.cfg`, усталяваўшы `Language = blr`.

## Пераклад

- Першапачатковы машынны пераклад — выпраўленні ад супольнасці вітаюцца праз PR або Issue.
- Плагін / аснова: https://github.com/9138noms/NuclearOption-TranslationToolkit

## Ліцэнзія шрыфта

Exo 2 — [SIL Open Font License 1.1](https://fonts.google.com/specimen/Exo+2)
