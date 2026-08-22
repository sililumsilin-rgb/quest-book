# Quest Book

**[English](#english) · [Русский](#русский)**

![A hand-drawn orc using Quest Book at a computer](quest-book-orc-main.png)

Quest Book is a standalone local journal for personal quests and goals, inspired by the classic fantasy MMORPG interface. Separate English and Russian editions are available for macOS and Windows.

> Current version: **a0.0.8 (alpha)**  
> Platforms: **macOS 12+ on Apple Silicon** and **Windows 10/11 x64**

## Download

### macOS — Apple Silicon

- **English:** [Quest Book EN a0.0.8 for macOS](https://github.com/sililumsilin-rgb/quest-book/releases/download/a0.0.8-macos/QuestBook-EN-a0.0.8-macOS-AppleSilicon.zip)
- **Русский:** [Quest Book RU a0.0.8 для macOS](https://github.com/sililumsilin-rgb/quest-book/releases/download/a0.0.8-macos/QuestBook-a0.0.8-macOS-AppleSilicon.zip)
- [macOS release notes and checksums](https://github.com/sililumsilin-rgb/quest-book/releases/tag/a0.0.8-macos)

These builds are for Macs with Apple Silicon (M1, M2, M3, M4, or newer). Intel Macs are not supported by the current release.

### Windows — x64

- **English:** [Quest Book EN a0.0.8 for Windows](https://github.com/sililumsilin-rgb/quest-book/releases/download/a0.0.8/QuestBook-EN-a0.0.8-Windows-x64.zip)
- **Русский:** [Quest Book RU a0.0.8 для Windows](https://github.com/sililumsilin-rgb/quest-book/releases/download/a0.0.8/QuestBook-a0.0.8-Windows-x64.zip)
- [Windows release notes and checksums](https://github.com/sililumsilin-rgb/quest-book/releases/tag/a0.0.8)

See the complete [changelog](CHANGELOG.md).

## English

Quest Book is an independent application. It does not modify game files, connect to a game account or server, or track in-game quests automatically. You create and manage all quests, descriptions, and objectives yourself.

### Install on macOS

1. Download and fully extract `QuestBook-EN-a0.0.8-macOS-AppleSilicon.zip`.
2. Optionally drag `Quest Book EN.app` to the Applications folder.
3. On first launch, Control-click or right-click the application, choose **Open**, and confirm.

macOS may display a security warning because the current alpha build uses a local ad-hoc signature and is not notarized with a paid Apple Developer account.

Keyboard shortcuts are not supported in the current macOS build. To hide or show Quest Book, left-click its icon in the menu bar at the top of the screen.

### Install on Windows

1. Download and fully extract `QuestBook-EN-a0.0.8-Windows-x64.zip` into a separate folder.
2. Run `QuestBookEN.exe`.

Do not move the EXE by itself: the `web` folder and all other files from the archive must remain next to it. Windows SmartScreen may show an unknown-publisher warning because the alpha build is not signed with a paid developer certificate. If you downloaded it from this official repository, choose **More info → Run anyway**.

### Features

- create, edit, and delete quests;
- organize quests into collapsible trees;
- add objectives and mark them complete;
- keep short and full quest descriptions;
- set difficulty and color independently for every quest;
- configure rewards, quest tracking, and interface sounds;
- choose 100%, 130%, or 150% interface scale;
- hide the application and restore it quickly;
- save all changes automatically on your computer.

### Privacy and local data

Quest Book works locally and does not require an account. Your quests and settings are stored only on your computer:

```text
macOS EN: ~/Library/Application Support/Quest Book EN/quests.json
macOS RU: ~/Library/Application Support/Quest Book/quests.json
Windows EN: %APPDATA%\Quest Book EN\quests.json
Windows RU: %APPDATA%\Quest Book\quests.json
```

The application does not send your data to the developer and does not use cloud synchronization, telemetry, or analytics. Its core features work without an internet connection. The support link opens Boosty in your external browser only when you click it.

The English and Russian editions can be used on the same computer because they keep their data separately. To back up your journal, copy its `quests.json` file.

### System requirements

- **macOS:** macOS 12 Monterey or newer and an Apple Silicon Mac. The current build does not support Intel Macs.
- **Windows:** 64-bit Windows 10 or Windows 11 and Microsoft Edge WebView2 Runtime.

WebView2 is already installed on most modern Windows computers. If it is missing, install [Evergreen WebView2 Runtime from Microsoft](https://developer.microsoft.com/microsoft-edge/webview2/).

## Русский

Quest Book — самостоятельный журнал заданий для личных целей. Программа не изменяет файлы игры, не подключается к игровому аккаунту или серверу и не отслеживает игровые задания автоматически. Вы сами создаёте задания, описания и цели.

### Установка на macOS

1. Скачайте и полностью распакуйте `QuestBook-a0.0.8-macOS-AppleSilicon.zip`.
2. При желании перетащите `Quest Book.app` в папку «Программы».
3. При первом запуске нажмите приложение правой кнопкой мыши, выберите **«Открыть»** и подтвердите запуск.

macOS может показать предупреждение, потому что текущая альфа-сборка подписана локальной ad-hoc подписью и не нотарифицирована через платный аккаунт Apple Developer.

В текущей версии для macOS горячие клавиши не поддерживаются. Чтобы скрыть или снова показать Quest Book, нажмите левой кнопкой мыши его значок в строке меню в верхней части экрана.

### Установка на Windows

1. Скачайте и полностью распакуйте `QuestBook-a0.0.8-Windows-x64.zip` в отдельную папку.
2. Запустите `QuestBook.exe`.

Не переносите EXE-файл отдельно: папка `web` и остальные файлы из архива должны находиться рядом. Windows SmartScreen может показать предупреждение о неизвестном издателе, поскольку альфа-сборка не подписана платным сертификатом. Если архив скачан из этого официального репозитория, нажмите **«Подробнее» → «Выполнить в любом случае»**.

### Возможности

- создание, редактирование и удаление заданий;
- древовидная организация журнала;
- отдельные цели и отметки о выполнении;
- краткое и полное описание задания;
- настройка сложности и цвета каждого задания;
- награды, отслеживание заданий и игровые звуки интерфейса;
- масштабы интерфейса 100%, 130% и 150%;
- быстрое скрытие и восстановление приложения;
- автоматическое локальное сохранение.

### Конфиденциальность и локальные данные

Quest Book работает локально и не требует регистрации. Все задания и настройки хранятся только на вашем компьютере. Пути к файлам перечислены в разделе [Privacy and local data](#privacy-and-local-data) выше.

Программа не отправляет данные разработчику и не использует облачную синхронизацию, телеметрию или аналитику. Основные функции работают без интернета. Ссылка поддержки открывает Boosty во внешнем браузере только после вашего нажатия.

EN и RU можно использовать одновременно: они сохраняют данные раздельно. Для резервной копии достаточно скопировать соответствующий файл `quests.json`.

### Системные требования

- **macOS:** macOS 12 Monterey или новее и Mac с Apple Silicon. Текущая сборка не поддерживает Intel Mac.
- **Windows:** 64-битная Windows 10 или Windows 11 и Microsoft Edge WebView2 Runtime.

## Project status and disclaimer

Quest Book a0.0.8 is an alpha release. Please report reproducible problems through GitHub Issues and include your operating system and the edition you used.

This is an unofficial fan-made project and is not affiliated with, endorsed by, or sponsored by Blizzard Entertainment. Warcraft, World of Warcraft, and related names and assets belong to their respective rights holders.

This repository distributes compiled builds and documentation. The source code is not published here.
