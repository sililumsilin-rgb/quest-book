# Quest Book a0.0.8 — macOS Apple Silicon

The English and Russian editions are included in the same release. This is the first public macOS release of the standalone local quest journal.

Русская и английская версии входят в один релиз. Это первый публичный релиз самостоятельного локального журнала заданий для macOS.

![Quest Book English interface](https://raw.githubusercontent.com/sililumsilin-rgb/quest-book/main/quest-book-interface-en.png)

## Downloads / Файлы

- **EN:** `QuestBook-EN-a0.0.8-macOS-AppleSilicon.zip` — open `Quest Book EN.app`.
- **RU:** `QuestBook-a0.0.8-macOS-AppleSilicon.zip` — откройте `Quest Book.app`.

These builds are only for Macs with Apple Silicon (M1, M2, M3, M4, or newer). Intel Macs are not supported by this release.

Сборки предназначены только для Mac с Apple Silicon (M1, M2, M3, M4 или новее). Intel Mac в этом релизе не поддерживаются.

## Install and first launch / Установка и первый запуск

1. Fully extract the selected ZIP archive. / Полностью распакуйте выбранный ZIP-архив.
2. Optionally move the application to the Applications folder. / При желании перенесите приложение в папку «Программы».
3. On first launch, Control-click or right-click the application, choose **Open**, and confirm. / При первом запуске нажмите приложение правой кнопкой мыши, выберите **«Открыть»** и подтвердите запуск.

macOS may show a security warning because this alpha build uses a local ad-hoc signature and is not notarized with a paid Apple Developer account.

macOS может показать предупреждение, потому что альфа-сборка подписана локальной ad-hoc подписью и не нотарифицирована через платный аккаунт Apple Developer.

## macOS controls / Управление в macOS

Keyboard shortcuts are not supported in the current macOS build. Left-click the Quest Book icon in the menu bar at the top of the screen to hide or show the application. Right-click the icon to open the Show / Hide and Quit menu.

В текущей версии для macOS горячие клавиши не поддерживаются. Чтобы скрыть или снова показать приложение, нажмите левой кнопкой мыши значок Quest Book в строке меню в верхней части экрана. Правый клик открывает меню «Показать / скрыть» и «Выход».

## Included / Что входит

- complete English and Russian editions with separate application data;
- native macOS application shell using Cocoa and WKWebView;
- menu bar icon for quick show, hide, and quit actions;
- quest trees, objectives, descriptions, rewards, difficulty and color settings;
- interface sounds and 100%, 130%, and 150% scale options;
- automatic local saving with no account, cloud synchronization, telemetry, or analytics.

## Local data / Локальные данные

```text
EN: ~/Library/Application Support/Quest Book EN/quests.json
RU: ~/Library/Application Support/Quest Book/quests.json
```

All quests and settings remain on your Mac. The English and Russian editions can be used together because they save data separately.

Все задания и настройки остаются на вашем Mac. EN и RU можно использовать одновременно: данные сохраняются раздельно.

## Requirements / Требования

- macOS 12 Monterey or newer;
- a Mac with Apple Silicon.

## SHA-256

```text
7e369f00877de904617ec12237a5170975a6d745c0f90581a21f44dc1f69a42b  QuestBook-EN-a0.0.8-macOS-AppleSilicon.zip
85105c3ba40b39c32df1290cf7a495856dcdf7094193a8d940b315694af35bc9  QuestBook-a0.0.8-macOS-AppleSilicon.zip
```

This is an unofficial fan-made project and is not affiliated with Blizzard Entertainment.
