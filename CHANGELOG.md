# Quest Book changelog / История изменений

English comes first. Русская версия находится ниже.

## English

### a0.0.8

- added native macOS editions for Apple Silicon with macOS 12+ support;
- added a menu bar icon for instant show, hide, and quit actions on macOS;
- keyboard shortcuts are not supported in the current macOS build; visibility is controlled by left-clicking the menu bar icon;
- macOS EN and RU editions keep their data in separate local folders and can be used together;
- added the complete English edition with English artwork, fonts, interface text, native Windows messages, tray commands, and editor text;
- the EN edition contains the complete feature set of the Russian a0.0.8 build;
- EN and RU editions use independent application data and WebView2 storage and can be installed together;
- the interface is rendered in a background window outside the visible screen before being shown;
- frame readiness is confirmed from the WebView2 surface, preventing an intermediate black startup frame;
- the rendered surface stays ready off-screen while minimized to the tray for immediate restoration;
- the quest creation and editing window is prepared using the same background-rendering method.

### a0.0.7

- fixed the black startup screen that could freeze on some Windows computers;
- WebView2 remains active while loading and receives a continuous rendering surface;
- added a lightweight game-style loading background behind the main window and editor instead of a black frame.

### a0.0.6

- the window is shown only after the interface and game-style resources finish loading;
- difficulty and color can be configured independently for every quest;
- added settings for short-objective and full-description text size;
- the selected quest uses the original-style highlight texture tinted by its difficulty;
- quest text moves slightly downward while pressed, matching the game-style interaction;
- improved the rewards section to better match the original visual reference.

### a0.0.5

- removed the black background around the separate quest editor window;
- moved game-style button labels one pixel upward.

### a0.0.4

- corrected button states and label positioning in the quest editor;
- corrected close buttons and objective removal controls;
- a new quest now opens without an empty objective, and objectives are added with a separate button.

### a0.0.3

- transparent window edges now preserve real transparency;
- scroll thumbs can be dragged with the left mouse button;
- added an independent interface-sound volume setting;
- quest creation and editing now use a separate movable 598×502 window;
- updated the create button, objective borders, editor window, and rewards.

### a0.0.2

- rebuilt the interface from the PSD layout without distorting its proportions;
- added 100%, 130%, and 150% interface scales;
- added sound, quest color, quest limit, and global shortcut settings;
- added rewards, existing-tree selection, and new-tree creation;
- added game-style sounds, a confirmation window, and an About section.

---

## Русский

### a0.0.8

- добавлены нативные версии для macOS 12+ и Mac с Apple Silicon;
- в macOS добавлен значок в строке меню для быстрого показа, скрытия и выхода;
- горячие клавиши в текущей версии для macOS не поддерживаются; скрытие и показ выполняются левым кликом по значку в строке меню;
- версии EN и RU для macOS хранят данные в разных локальных папках и могут использоваться одновременно;
- добавлена полноценная английская версия с английскими изображениями, шрифтами, интерфейсом, системными сообщениями Windows, командами в трее и текстом редактора;
- английская версия включает полный набор возможностей русской сборки a0.0.8;
- EN и RU используют разные папки данных и хранилища WebView2 и могут быть установлены одновременно;
- интерфейс полностью отрисовывается в фоновом окне за пределами экрана до показа пользователю;
- готовность кадра подтверждается по поверхности WebView2, поэтому окно появляется без промежуточного чёрного кадра;
- при сворачивании в трей поверхность остаётся отрисованной за пределами экрана для мгновенного восстановления;
- окно создания и редактирования задания подготавливается таким же способом.

### a0.0.7

- исправлено зависание на чёрном стартовом экране на части Windows-компьютеров;
- WebView2 больше не скрывается во время загрузки и получает непрерывную поверхность отрисовки;
- под главным окном и редактором добавлен лёгкий игровой фон загрузки вместо чёрного кадра.

### a0.0.6

- окно показывается только после полной загрузки интерфейса и игровых ресурсов;
- сложность и цвет теперь задаются отдельно для каждого задания;
- в настройках добавлен размер текста краткой цели и полного описания;
- выбранное задание подсвечивается оригинальной игровой текстурой с цветом его сложности;
- текст задания слегка смещается вниз при нажатии, как в интерфейсе игры;
- оформление раздела наград приближено к оригинальному игровому образцу.

### a0.0.5

- убран чёрный фон вокруг отдельного окна задания;
- текст игровых кнопок дополнительно поднят на один пиксель.

### a0.0.4

- исправлены состояния кнопок и положение текста в окне задания;
- исправлены крестики закрытия и удаления задачи;
- новое задание открывается без пустой задачи, поле добавляется отдельной кнопкой.

### a0.0.3

- прозрачные боковые края окна теперь сохраняют настоящую прозрачность;
- ползунки прокрутки можно перетаскивать левой кнопкой мыши;
- добавлена отдельная регулировка громкости звуков интерфейса;
- создание и редактирование задания открывается отдельным перемещаемым окном 598×502;
- обновлены кнопка создания, рамки задач, окно создания/редактирования и награды.

### a0.0.2

- интерфейс пересобран по точной разметке PSD без искажения пропорций;
- добавлены масштабы 100%, 130% и 150%;
- добавлены настройки звука, цвета заданий, лимита и глобальной горячей клавиши;
- добавлены награды, выбор существующего древа и создание нового;
- добавлены игровые звуки, окно подтверждения и раздел «О программе».
