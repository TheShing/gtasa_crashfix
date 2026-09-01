# crashes v2.4 — Modified version

## Русский

Неофициальная модифицированная версия **crashes.asi v2.4** от **Whitetigerswt**.

Данная версия основана на релизе v2.4 и содержит несколько исправлений и небольших изменений поведения плагина.

> Дальнейшая поддержка и развитие данной модификации не планируются.

### Изменения

- Исправлен фикс урона при перелезании через препятствия.  
  Теперь урон блокируется только во время фактического перелезания и только от падения. Остальные виды урона продолжают обрабатываться штатно.

- Исправлен софтлок при смерти в стоящем или медленно движущемся автомобиле.

- Добавлен параметр `interiormusic` в `crashes.cfg`, позволяющий включать или отключать музыку, играющую в интерьерах.  
  `interiormusic 1` включает оригинальную музыку GTA: San Andreas в интерьерах, а `interiormusic 0` отключает её.

### Модифицированная версия

Модификация, тестирование и проверка исправлений: **TheShing**

Анализ исходного кода, помощь в поиске причин ошибок и разработке исправлений: **ChatGPT (OpenAI)**

---

## English

This is an unofficial modified version of **crashes.asi v2.4** by **Whitetigerswt**.

This version is based on the v2.4 release and contains several fixes and minor changes to the plugin's behavior.

> No further maintenance or development of this modification is planned.

### Changes

- Fixed the climbing damage fix.  
  Damage is now blocked only while the player is actually climbing and only for fall damage. All other damage types continue to be processed normally.

- Fixed a softlock that could occur when dying in a stationary or slowly moving vehicle.

- Added the `interiormusic` option to `crashes.cfg`, allowing interior music to be enabled or disabled.  
  `interiormusic 1` enables the original GTA: San Andreas interior music, while `interiormusic 0` disables it.

### Modified version

Modifications, testing and verification of the fixes: **TheShing**

Source code analysis, debugging assistance and implementation guidance: **ChatGPT (OpenAI)**

---

Fix GTA:SA Bugs ASI
=============

This mod does the following things:

- Fixes aproxamently 30 crashes that can occur in GTA:SA.
- Allows all resolutions and aspect ratios to be used
- Removes interior music.
- Removes clouds.
- Disables parts of the frame limiter to increase FPS.
- Fixes a couple of compatability problems with Windows 8.
- Implements Deji's StreamIni extender CLEO.
- Implements Ryosuke839's fastloader.asi - The game loads in about 2 seconds for me.


Requirements
-------
- GTA:SA
- ASI Loader: http://www.gtagarage.com/mods/show.php?id=8321

Credits
-------

most credits go to the MTA team, and the original code can be found at: https://code.google.com/p/mtasa-blue/

Credits: MTA:SA, Deji, 0x688, Ryosuke839