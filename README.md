
# Беларускі пераклад для Stardew Valley


**Belarusizacja Stardew Valley** - гэта поўны пераклад гульні Stardew Valley на беларускую мову.  
Люстра перакладу разам з усімі патрэбнымі модамі для [PC](https://mega.nz/folder/C2higIIC#iAwKE4OBRBG7QQlGLjmKyg), [Android](https://mega.nz/folder/LuwHVQyB#GOsLjoFvrYdbW-slKhz11w)

### Лакалізацыю гэтаксама можна ўсталяваць праз Vortex!!!

Аўтары перакладу: łokar (dymniska & Ueschar)  
Рэдактар: Cactusovič  
Асаблівая падзяка <span style="color:#ff0000"><3</span>  
observr - Помач з перакладам, пруфрыдынг, іншае меркаванне  
dziaǔčo - Помач з тэставаннем перакладу  
Danielle Tłumač - аўтарка папраўленага шрыфту  

---

# Інструкцыя ўсталявання Windows, Mac, Linux, Steam Deck

(Інструкцыя для Android ніжэй)

## 1. Загрузка неабходных файлаў

- Каб гульня замяніла арыгінальны тэкст беларускім перакладам, загрузіце:
  - [Архіў мода з старонкі "Файлы"](https://www.nexusmods.com/stardewvalley/mods/27171?tab=files&file_id=109760)
  - [SMAPI installer](https://smapi.io/) (найнавейшая версія)
  - [ContentPatcher](https://www.nexusmods.com/stardewvalley/mods/1915)
  - [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098)

## 2. Усталяванне SMAPI

*Дадатковы крок для MacOS:*

1. Увайдзіце ў *Сістэмныя налады > Прыватнасць і бяспека (System Settings > Privacy and Security)*.
2. Праверце, ці відаць *Налады распрацоўшчыка (Developer Tools)*. Калі іх няма, запусціце тэрмінал праз Spotlight і ўвядзіце каманду:  
   > spctl developer-mode enable-terminal
3. Націсніце *Налады распрацоўшчыка (Developer Tools)*.
4. Дадайце тэрмінал у спіс ([скрыншот](https://stardewvalleywiki.com/File:Fix_macOS_security_permissions_2.png)).
5. Перазапусціце кампутар.

Разархівуйце тэчку "SMAPI installer" у зручнае месца на вашым камп'ютары і адкрыйце яе.  
Унутры будуць некалькі файлаў для ўсталявання на розных сістэмах. У залежнасці ад сістэмы выконваем адпаведны файл:  
a. Windows - install on Windows.bat,  
b. MacOS - install on macOS.command,  
c. Linux - install on Linux.sh  
d. Steam deck - install on Linux.sh  

Запусціце гэты файл.  
1) Адкрыецца кансоль з выбарам шляху да тэчкі з гульнёй. Выберыце адзін з паказаных варыянтаў, увядзіце адпаведны нумар у кансоль і націсніце Enter.

> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

2) Далей вам прапаноўваецца ўсталяваць або выдаліць SMAPI. Увядзіце "1" і націсніце Enter для ўсталявання

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

3) Праверка ўсталявання - Калі ўсё прайшла паспяхова, вы ўбачыце наступнае паведамленне:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install):  
>     "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%  
> If you don't use Steam, launch StardewModdingAPI.exe in your game folder to play with mods.

<span style="color:#ffff00">[!] Калі ў вас Steam версія гульні, рэкамендуем скапіяваць тэкст з другой лінейкі. Мае выглядаць падобным чынам:</span>

> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

<span style="color:#ffff00">Гэта вам спатрэбіцца пазней, каб уключыць магчымасць атрымоўваць дасягненні ў Steam.</span>

## 3. Усталюйце тэчкі модаў Content Patcher Generic Mod Config Menu і Беларусізацыю ў .../Stradew valley/Mods

a. Дадатковы крок для Linux версіі – усталяваць тэрмінал xterm (Ён не мусіць быць вашым прадвызначаным тэрміналам)

---

# Запуск Гульні

## 1. Для Mac, Linux, Steam Deck –

Усталяванне завершанае, запускаем гульню як звычайна

## 2. Версія без Steam

- Запускайце гульню праз файл "StardewModdingAPI.exe" замест звычайнага "Stardew Valley.exe". Гэты файл мае быць у каранёвай тэчцы з гульнёй, напрыклад:

> C:\Games\Stardew Valley

Рэкамендуем стварыць ярлык для гэтага файла, каб было зручней запускаць гульню.

## 3. Версія для Steam (Запуск праз бібліятэку Steam і атрыманне дасягненняў)

1) Скапіюйце каманду з усталявальніка SMAPI, якая з'яўляецца пасля паведамлення:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install)

Звычайна каманда выглядае так:

> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

2) Адкрыйце Steam, зайдзіце ва **ўласцівасці** Stardew Valley (пстрык ПКМ на гульню ў бібліятэцы -> Properties), і ўстаўце каманду ў радок **LAUNCH OPTIONS** на першай укладцы **General**.  
3) Запусціце гульню праз бібліятэку Steam.

---

# Змена правапісу і шрыфтоў

- У меню гульні можна выбраць афіцыйны ці клясычны(БКП-2005) правапіс, а таксама 1 з 3 шрыфтоў. Каб усё адпаведна працавала, упэўніцеся, што ўсталявалі [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098).  
- У левым ніжнім куце экрану будзе кнопка з значком "хэштэга", якая адкрывае меню модаў, улучаючы Беларусізатар (гл. Скрыншоты). Там трэба выбраць мод, што нас цікавіць (Stardew Valley Belarusian). Пасля змены правапісу ці шрыфту перазапусціце гульню.

---

# Інструкцыя для Android

## 1. Загрузка неабходных файлаў

- Каб гульня замяніла арыгінальны тэкст беларускім перакладам, загрузіце:
  - [Архіў мода з старонкі "Файлы"](https://www.nexusmods.com/stardewvalley/mods/27171?tab=files&file_id=109760)
  - [ContentPatcher](https://www.nexusmods.com/stardewvalley/mods/1915)

## 2. Усталяванне SMAPI

1) Спампуйце [SMAPI Launcher APK](https://github.com/NRTnarathip/SMAPILoader/releases) (файл мусіць называцца прыкладна так: ***SMAPI.Launcher.vx.x.x.apk***)  
2) [Усталюйце спампаваны лаўнчар](https://www.greenbot.com/article/2452614/how-to-sideload-an-app-onto-your-android-phone-or-tablet.html)  
3) [Спампуйце SMAPI](https://github.com/NRTnarathip/SMAPI-Android-1.6/releases) (файл мусіць называцца прыкладна так: ***SMAPI.4.x.x-xxxx.zip***)  
4) Запусціце лаўнчар SMAPI.  
5) Націсніце кнопку "Install SMAPI From Zip" (Усталяваць SMAPI з ZIP архіву)  
6) Выберыце спампаваны файл SMAPI  
7) Пачакайце, пакуль лаўнчар не паведаміць, што SMAPI паспяхова ўсталяваны.  
8) Націсніце "Start Game" (Пачаць гульню). Цяпер запускаць Stardew Valley трэба будзе пра гэты лаўнчар.  

Больш дакладную інструкцыю можна прачытаць на афіцыяльнай [wiki](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Android).

---

# Адладка

## - Калі пераклад не паказваецца пасля першага запуску

Мабыць, гульня самастойна не ўлучыла беларусізатар. Тады трэба пстрыкнуць па іконцы выбару моваў (правы ніжні кут). Потым у новым вакне трэба націснуць на стрэлачку з правага боку. (Гл. Скрыншот №3) Тады ў спісе моў з’явіцца беларуская.

Калі пераклад раптам не з'явіўся пасля першага запуску гульні, пераканайцеся, што ўсе файлы знаходзяцца ў патрэбных тэчках і вы запускаеце гульню праз StardewModdingAPI.exe, або з выкарыстаннем мадыфікаванага параметра запуску Steam.

---

*Гэтая інструкцыя дапаможа вам усталяваць беларускую лакалізацыю для Stardew Valley. Калі вы сутыкнуліся з праблемамі, звяртайцеся да [дапаможніка да ўсталявання SMAPI](https://smapi.io/install) або звяртайцеся па дапамогу да супольнасці.*

### Тэлеграм аўтараў:
[Ueschar](https://t.me/Ueschar)  
[dymniska](https://t.me/dymniska)

### Таксама варта зірнуць:
[Тэлеграм-канал з навінамі аб перакладзе](https://t.me/trojantranslation)  
[Твітар з навінамі аб перакладзе](https://x.com/lokar_lak)  
[Дыскорд сервер беларускай супольнасці](https://discord.gg/wCPEK5kFUj)

# Белорусский перевод для Stardew Valley

**Белорусизация Stardew Valley** - это полный перевод игры Stardew Valley на белорусский язык.  
Зеркало перевода вместе со всеми необходимыми модами для [PC](https://mega.nz/folder/C2higIIC#iAwKE4OBRBG7QQlGLjmKyg), [Android](https://mega.nz/folder/LuwHVQyB#GOsLjoFvrYdbW-slKhz11w)

Авторы перевода: łokar (dymniska & Ueschar)  
Редактор: Cactusovič  
Особая благодарность <span style="color:#ff0000"><3</span>  
observr - Помощь с переводом, proofreading, другое мнение  
dziaǔčo - Помощь с тестированием перевода  
Danielle Tłumač - авторка исправленного шрифта  

---

# Инструкция установки Windows, Mac, Linux, Steam Deck

(Инструкция для Android ниже)

## 1. Загрузка необходимых файлов

Чтобы игра заменила оригинальный текст белорусским переводом, скачайте:
- [Архив мода со страницы "Файлы"](https://www.nexusmods.com/stardewvalley/mods/27171?tab=files&file_id=109760)
- [SMAPI installer](https://smapi.io/) (самая новая версия)
- [ContentPatcher](https://www.nexusmods.com/stardewvalley/mods/1915)
- [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098)

## 2. Установка SMAPI

*Дополнительный шаг для MacOS:*

1. Войдите в *Системные настройки > Приватность и безопасность (System Settings > Privacy and Security)*.
2. Проверьте, видны ли *Настройки разработчика (Developer Tools)*. Если их нет, запустите терминал через Spotlight и введите команду:  
   > spctl developer-mode enable-terminal
3. Нажмите *Настройки разработчика (Developer Tools)*.
4. Добавьте терминал в список ([скриншот](https://stardewvalleywiki.com/File:Fix_macOS_security_permissions_2.png)).
5. Перезапустите компьютер.

Разархивируйте папку "SMAPI installer" в удобное место на вашем компьютере и откройте её.  
Внутри будут несколько файлов для установки на разных системах. В зависимости от системы выполняем соответствующий файл:  
a. Windows - install on Windows.bat,  
b. MacOS - install on macOS.command,  
c. Linux - install on Linux.sh  
d. Steam deck - install on Linux.sh  

Запустите этот файл.  
Откроется консоль с выбором пути к папке с игрой. Выберите один из показанных вариантов, введите соответствующий номер в консоль и нажмите Enter.

> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

Далее вам предлагается установить или удалить SMAPI. Введите "1" и нажмите Enter для установки

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

Проверка установки - Если всё прошло успешно, вы увидите следующее сообщение:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install):  
>     "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%  
> If you don't use Steam, launch StardewModdingAPI.exe in your game folder to play with mods.

<span style="color:#ffff00">[!] Если у вас Steam версия игры, рекомендуем скопировать текст со второй строки. Должен выглядеть подобным образом:</span>

> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

<span style="color:#ffff00">Это вам понадобится позже, чтобы включить возможность получать достижения в Steam.</span>

## 3. Установите папки модов Content Patcher Generic Mod Config Menu и Белорусизацию в .../Stradew valley/Mods

a. Дополнительный шаг для Linux версии – установить терминал xterm (Он не должен быть вашим предустановленным терминалом)

---

# Запуск Игры

## 1. Для Mac, Linux, Steam Deck –

Установка завершена, запускаем игру как обычно

## 2. Версия без Steam

Запускайте игру через файл "StardewModdingAPI.exe" вместо обычного "Stardew Valley.exe". Этот файл должен быть в корневой папке с игрой, например:

> C:\Games\Stardew Valley

Рекомендуем создать ярлык для этого файла, чтобы было удобнее запускать игру.

## 3. Версия для Steam (Запуск через библиотеку Steam и получение достижений)

Скопируйте команду из установщика SMAPI, которая появляется после сообщения:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install)

Обычно команда выглядит так:

> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

Откройте Steam, зайдите в **свойства** Stardew Valley (щелк ПКМ на игру в библиотеке -> Properties), и вставьте команду в строку **LAUNCH OPTIONS** на первой вкладке **General**.  
Запустите игру через библиотеку Steam.

---

# Изменение правописания и шрифтов

- В меню игры можно выбрать официальное или классическое(БКП-2005) правописание, а также 1 из 3 шрифтов. Чтобы всё соответственно работало, убедитесь, что установили [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098).  
- В левом нижнем углу экрана будет кнопка с значком "хэштега", которая открывает меню модов, включая Белорусизатор (см. Скриншоты). Там нужно выбрать мод, который нас интересует (Stardew Valley Belarusian). После изменения правописания или шрифта перезапустите игру.

---

# Инструкция для Android

## 1. Загрузка необходимых файлов

Чтобы игра заменила оригинальный текст белорусским переводом, скачайте:
- [Архив мода со страницы "Файлы"](https://www.nexusmods.com/stardewvalley/mods/27171?tab=files&file_id=109760)
- [ContentPatcher](https://www.nexusmods.com/stardewvalley/mods/1915)

## 2. Установка SMAPI

1) Скачайте [SMAPI Launcher APK](https://github.com/NRTnarathip/SMAPILoader/releases) (файл должен называться примерно так: ***SMAPI.Launcher.vx.x.x.apk***)  
2) [Установите скачанный лаунчер](https://www.greenbot.com/article/2452614/how-to-sideload-an-app-onto-your-android-phone-or-tablet.html)  
3) [Скачайте SMAPI](https://github.com/NRTnarathip/SMAPI-Android-1.6/releases) (файл должен называться примерно так: ***SMAPI.4.x.x-xxxx.zip***)  
4) Запустите лаунчер SMAPI.  
5) Нажмите кнопку "Install SMAPI From Zip" (Установить SMAPI из ZIP архива)  
6) Выберите скачанный файл SMAPI  
7) Подождите, пока лаунчер не сообщит, что SMAPI успешно установлен.  
8) Нажмите "Start Game" (Начать игру). Теперь запускать Stardew Valley нужно будет через этот лаунчер.  

Более подробную инструкцию можно прочитать на официальной [wiki](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Android).

---

# Отладка

## - Если перевод не показывается после первого запуска

Возможно, игра самостоятельно не включила белорусизатор. Тогда нужно кликнуть по иконке выбора языков (правый нижний угол). Затем в новом окне нужно нажать на стрелочку с правой стороны. (См. Скриншот №3) Тогда в списке языков появится белорусский.

Если перевод вдруг не появился после первого запуска игры, убедитесь, что все файлы находятся в нужных папках и вы запускаете игру через StardewModdingAPI.exe, или с использованием модифицированного параметра запуска Steam.

---

*Эта инструкция поможет вам установить белорусскую локализацию для Stardew Valley. Если вы столкнулись с проблемами, обращайтесь к [руководству по установке SMAPI](https://smapi.io/install) или обращайтесь за помощью к сообществу.*

### Телеграм авторов:
[Ueschar](https://t.me/Ueschar)  
[dymniska](https://t.me/dymniska)

### Также стоит взглянуть:
[Телеграм-канал с новостями о переводе](https://t.me/trojantranslation)  
[Твиттер с новостями о переводе](https://x.com/lokar_lak)  
[Дискорд сервер белорусского сообщества](https://discord.gg/wCPEK5kFUj)