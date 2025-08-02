# Flipper_tools_for_iphone
# 🍎 Apple Tools for Flipper (ATFf)
p.s. это могло бы весить 320кг

## 🇷🇺 Русская версия

Полнофункциональный набор инструментов для работы с iPhone на Flipper Zero. Приложение предоставляет полный доступ к информации об устройстве, управление данными и резервное копирование.

### 🎯 Основные функции

#### 📱 Device Info (Информация об устройстве)
- **Название устройства** - отображает модель iPhone
- **Модель устройства** - внутренний код модели
- **Версия iOS** - текущая версия операционной системы
- **Серийный номер** - уникальный идентификатор устройства
- **IMEI** - международный идентификатор мобильного оборудования
- **Статус подключения** - текущее состояние соединения
- **Счетчик подключений** - количество успешных подключений

#### 🔋 Battery Info (Информация о батарее)
- **Уровень заряда** - текущий процент заряда (0-100%)
- **Статус зарядки** - заряжается/не заряжается
- **Здоровье батареи** - процент износа батареи
- **Количество циклов** - количество полных циклов зарядки
- **Температура** - текущая температура батареи в градусах Цельсия
- **Рекомендации** - советы по уходу за батареей

#### 💾 Storage Info (Информация о хранилище)
- **Общий объем** - полная емкость устройства
- **Использованное место** - занятое пространство
- **Свободное место** - доступное пространство
- **Разбивка по категориям:**
  - 📸 Фотографии и видео
  - 📱 Приложения
  - ⚙️ Системные файлы
  - 📁 Другие данные

#### 📦 Backup Manager (Менеджер резервных копий)
- **Создание резервной копии** - полное резервное копирование
- **Восстановление** - восстановление из резервной копии
- **Управление копиями** - просмотр и удаление копий
- **Экспорт данных** - выгрузка данных в различных форматах

#### 📱 App Manager (Управление приложениями)
- **Общее количество** - все установленные приложения
- **Пользовательские приложения** - загруженные пользователем
- **Системные приложения** - предустановленные приложения
- **Категории приложений:**
  - Социальные сети
  - Игры
  - Продуктивность
  - Утилиты
  - Развлечения
- **Информация о хранилище** - размер каждого приложения

#### 👥 Contacts Manager (Управление контактами)
- **Общее количество контактов** - все сохраненные контакты
- **Избранные контакты** - контакты в избранном
- **Недавние контакты** - недавно использованные
- **Категории контактов:**
  - Семья
  - Работа
  - Друзья
  - Другие
- **Экспорт контактов** - выгрузка в vCard формате

#### 💬 Messages Manager (Управление сообщениями)
- **Общее количество разговоров** - все чаты
- **Непрочитанные сообщения** - новые сообщения
- **Общее количество сообщений** - все сообщения
- **Типы сообщений:**
  - SMS
  - iMessage
  - MMS
- **Экспорт сообщений** - выгрузка истории переписки

#### 📅 Calendar Manager (Управление календарем)
- **Общее количество событий** - все события
- **Предстоящие события** - будущие события
- **Количество календарей** - активные календари
- **Категории событий:**
  - Работа
  - Личное
  - Семья
  - Здоровье
  - Другое
- **Синхронизация календаря** - синхронизация с облаком

#### 📝 Notes Manager (Управление заметками)
- **Общее количество заметок** - все заметки
- **Закрепленные заметки** - важные заметки
- **Размер заметок** - общий объем
- **Категории заметок:**
  - Работа
  - Личное
  - Идеи
  - Покупки
  - Другое
- **Экспорт заметок** - выгрузка заметок

#### 📸 Photos Manager (Управление фотографиями)
- **Общее количество фотографий** - все фото
- **Общее количество видео** - все видео
- **Количество альбомов** - созданные альбомы
- **Размер фотографий** - общий объем
- **Экспорт фотографий** - выгрузка фото и видео

#### 🎵 Music Manager (Управление музыкой)
- **Общее количество песен** - вся музыка
- **Количество плейлистов** - созданные плейлисты
- **Количество альбомов** - музыкальные альбомы
- **Размер музыки** - общий объем
- **Экспорт плейлистов** - выгрузка плейлистов

#### ⚙️ Settings (Настройки)
- **Автоматическое резервное копирование** - настройка авто-бэкапов
- **Уведомления** - настройка звуковых и визуальных уведомлений
- **Таймаут подключения** - время ожидания подключения
- **Удержание данных** - период хранения данных
- **О приложении** - информация о версии

### 🚀 Установка

#### Способ 1: Автоматическая установка
```bash
./install_atfp.sh
```

#### Способ 2: Ручная установка
1. Подключите Flipper Zero к компьютеру
2. Скопируйте файлы в папку `applications_user/apple_tools/`
3. Перезапустите Flipper Zero

#### Способ 3: Через архив
1. Распакуйте `apple_tools_package.tar.gz` в корень Flipper Zero
2. Перезапустите устройство

### 📖 Использование

#### Основное меню
После запуска приложения вы увидите главное меню с разделами:
- 📱 Device Info
- 🔋 Battery Info  
- 💾 Storage Info
- 📦 Backup Manager
- 📱 App Manager
- 👥 Contacts
- 💬 Messages
- 📅 Calendar
- 📝 Notes
- 📸 Photos
- 🎵 Music
- ⚙️ Settings

#### Навигация
- **Кнопка BACK** - возврат в предыдущее меню
- **Кнопка OK** - выбор пункта меню
- **Кнопки UP/DOWN** - навигация по меню

#### Подключение iPhone
1. Запустите приложение на Flipper Zero
2. Подключите iPhone через USB кабель
3. Разблокируйте iPhone
4. Подтвердите доверие к Flipper Zero на iPhone
5. Приложение автоматически определит подключение

### 🔧 Технические детали

#### Системные требования
- **Flipper Zero Firmware**: 18.0.0 и выше
- **iPhone**: любая модель с USB подключением
- **iOS**: 12.0 и выше
- **USB кабель**: качественный кабель для передачи данных

#### Архитектура приложения
- **Модульная структура** - каждый раздел независим
- **Scene Manager** - управление экранами приложения
- **View Dispatcher** - переключение между представлениями
- **Event-driven** - событийная архитектура

#### API и библиотеки
- **Flipper Zero API** - основной API устройства
- **GUI Framework** - графический интерфейс
- **Notification System** - система уведомлений
- **Storage API** - работа с файловой системой

### 📊 Все функции

#### ✅ Реализованные функции
- [x] Информация об устройстве
- [x] Мониторинг батареи
- [x] Анализ хранилища
- [x] Управление приложениями
- [x] Резервное копирование
- [x] Управление контактами
- [x] Управление сообщениями
- [x] Управление календарем
- [x] Управление заметками
- [x] Управление фотографиями
- [x] Управление музыкой
- [x] Настройки и конфигурация

### 🐛 Устранение неполадок

#### Приложение не запускается
- Убедитесь, что прошивка совместима (18.0.0+)
- Проверьте, что все файлы на месте
- Перезапустите Flipper Zero

#### iPhone не определяется
- Убедитесь, что iPhone разблокирован
- Используйте качественный USB кабель
- Проверьте, что iPhone доверяет Flipper Zero
- Попробуйте другой USB порт

#### Нет данных в разделах
- Подключите iPhone и подождите несколько секунд
- Убедитесь, что iPhone разблокирован
- Проверьте соединение USB

#### Медленная работа
- Закройте другие приложения на Flipper Zero
- Убедитесь, что у устройства достаточно памяти
- Перезапустите Flipper Zero

### 🔒 Безопасность

#### Приватность данных
- Все данные обрабатываются локально на Flipper Zero
- Нет передачи данных на внешние серверы
- Информация не сохраняется постоянно

#### Безопасность подключения
- Используется стандартный USB протокол
- Нет доступа к паролям или ключам
- Только чтение информации об устройстве

### 📈 Производительность

#### Оптимизация памяти
- Эффективное использование RAM
- Освобождение памяти после использования
- Минимальное потребление ресурсов

#### Скорость работы
- Быстрое определение подключения
- Мгновенное обновление данных
- Плавная навигация по меню

### 🤝 Поддержка @byrbyrka telegram

#### Логирование
Приложение выводит подробные логи:
- Подключение/отключение iPhone
- Чтение информации об устройстве
- Ошибки и предупреждения
- Статистика использования

#### Отладка
Для отладки используйте консоль Flipper Zero:
```bash
# Просмотр логов
tail -f /dev/ttyUSB0
```

### 📝 Лицензия
Этот проект распространяется под лицензией MIT.

### 🙏 Благодарности
- Команде Flipper Zero за отличную платформу
- Сообществу разработчиков Flipper Zero
- Всем тестерам и пользователям

---

## 🇺🇸 English Version

A comprehensive toolkit for working with iPhone on Flipper Zero. The application provides full access to device information, data management, and backup functionality.

### 🎯 Main Features

#### 📱 Device Info
- **Device Name** - displays iPhone model
- **Device Model** - internal model code
- **iOS Version** - current operating system version
- **Serial Number** - unique device identifier
- **IMEI** - international mobile equipment identifier
- **Connection Status** - current connection state
- **Connection Counter** - number of successful connections

#### 🔋 Battery Info
- **Battery Level** - current charge percentage (0-100%)
- **Charging Status** - charging/not charging
- **Battery Health** - battery wear percentage
- **Cycle Count** - number of full charge cycles
- **Temperature** - current battery temperature in Celsius
- **Recommendations** - battery care tips

#### 💾 Storage Info
- **Total Capacity** - full device capacity
- **Used Space** - occupied space
- **Free Space** - available space
- **Breakdown by categories:**
  - 📸 Photos and Videos
  - 📱 Applications
  - ⚙️ System Files
  - 📁 Other Data

#### 📦 Backup Manager
- **Create Backup** - full backup creation
- **Restore** - restore from backup
- **Backup Management** - view and delete backups
- **Data Export** - export data in various formats

#### 📱 App Manager
- **Total Count** - all installed applications
- **User Applications** - user-downloaded apps
- **System Applications** - pre-installed applications
- **App Categories:**
  - Social Networks
  - Games
  - Productivity
  - Utilities
  - Entertainment
- **Storage Information** - size of each application

#### 👥 Contacts Manager
- **Total Contacts** - all saved contacts
- **Favorite Contacts** - contacts in favorites
- **Recent Contacts** - recently used contacts
- **Contact Categories:**
  - Family
  - Work
  - Friends
  - Others
- **Contact Export** - export in vCard format

#### 💬 Messages Manager
- **Total Conversations** - all chats
- **Unread Messages** - new messages
- **Total Messages** - all messages
- **Message Types:**
  - SMS
  - iMessage
  - MMS
- **Message Export** - export conversation history

#### 📅 Calendar Manager
- **Total Events** - all events
- **Upcoming Events** - future events
- **Calendar Count** - active calendars
- **Event Categories:**
  - Work
  - Personal
  - Family
  - Health
  - Other
- **Calendar Sync** - cloud synchronization

#### 📝 Notes Manager
- **Total Notes** - all notes
- **Pinned Notes** - important notes
- **Notes Size** - total volume
- **Note Categories:**
  - Work
  - Personal
  - Ideas
  - Shopping
  - Other
- **Notes Export** - export notes

#### 📸 Photos Manager
- **Total Photos** - all photos
- **Total Videos** - all videos
- **Album Count** - created albums
- **Photos Size** - total volume
- **Photos Export** - export photos and videos

#### 🎵 Music Manager
- **Total Songs** - all music
- **Playlist Count** - created playlists
- **Album Count** - music albums
- **Music Size** - total volume
- **Playlist Export** - export playlists

#### ⚙️ Settings
- **Auto Backup** - automatic backup settings
- **Notifications** - sound and visual notification settings
- **Connection Timeout** - connection wait time
- **Data Retention** - data storage period
- **About App** - version information

### 🚀 Installation

#### Method 1: Automatic Installation
```bash
./install_atfp.sh
```

#### Method 2: Manual Installation
1. Connect Flipper Zero to computer
2. Copy files to `applications_user/apple_tools/` folder
3. Restart Flipper Zero

#### Method 3: Via Archive
1. Extract `apple_tools_package.tar.gz` to Flipper Zero root
2. Restart device

### 📖 Usage

#### Main Menu
After launching the app, you'll see the main menu with sections:
- 📱 Device Info
- 🔋 Battery Info  
- 💾 Storage Info
- 📦 Backup Manager
- 📱 App Manager
- 👥 Contacts
- 💬 Messages
- 📅 Calendar
- 📝 Notes
- 📸 Photos
- 🎵 Music
- ⚙️ Settings

#### Navigation
- **BACK Button** - return to previous menu
- **OK Button** - select menu item
- **UP/DOWN Buttons** - menu navigation

#### iPhone Connection
1. Launch app on Flipper Zero
2. Connect iPhone via USB cable
3. Unlock iPhone
4. Confirm trust to Flipper Zero on iPhone
5. App will automatically detect connection

### 🔧 Technical Details

#### System Requirements
- **Flipper Zero Firmware**: 18.0.0 and above
- **iPhone**: any model with USB connection
- **iOS**: 12.0 and above
- **USB Cable**: quality data transfer cable

#### Application Architecture
- **Modular Structure** - each section is independent
- **Scene Manager** - application screen management
- **View Dispatcher** - switching between views
- **Event-driven** - event-driven architecture

#### API and Libraries
- **Flipper Zero API** - main device API
- **GUI Framework** - graphical interface
- **Notification System** - notification system
- **Storage API** - file system operations

### 📊 All Features

#### ✅ Implemented Features
- [x] Device Information
- [x] Battery Monitoring
- [x] Storage Analysis
- [x] Application Management
- [x] Backup Management
- [x] Contact Management
- [x] Message Management
- [x] Calendar Management
- [x] Notes Management
- [x] Photo Management
- [x] Music Management
- [x] Settings and Configuration

### 🐛 Troubleshooting

#### App Won't Start
- Ensure firmware is compatible (18.0.0+)
- Check that all files are in place
- Restart Flipper Zero

#### iPhone Not Detected
- Ensure iPhone is unlocked
- Use quality USB cable
- Check that iPhone trusts Flipper Zero
- Try different USB port

#### No Data in Sections
- Connect iPhone and wait a few seconds
- Ensure iPhone is unlocked
- Check USB connection

#### Slow Performance
- Close other apps on Flipper Zero
- Ensure device has enough memory
- Restart Flipper Zero

### 🔒 Security

#### Data Privacy
- All data is processed locally on Flipper Zero
- No data transmission to external servers
- Information is not permanently stored

#### Connection Security
- Standard USB protocol is used
- No access to passwords or keys
- Only reading device information

### 📈 Performance

#### Memory Optimization
- Efficient RAM usage
- Memory cleanup after use
- Minimal resource consumption

#### Speed
- Fast connection detection
- Instant data updates
- Smooth menu navigation

### 🤝 Support @byrbyrka telegram

#### Logging
App outputs detailed logs:
- iPhone connection/disconnection
- Reading device information
- Errors and warnings
- Usage statistics

#### Debugging
For debugging use Flipper Zero console:
```bash
# View logs
tail -f /dev/ttyUSB0
```

### 📝 License
This project is distributed under MIT license.

### 🙏 Acknowledgments
- Flipper Zero team for excellent platform
- Flipper Zero developer community
- All testers and users

---

**🇷🇺 Apple Tools for Flipper (ATFf) - полный набор инструментов для работы с iPhone! 🚀**

**🇺🇸 Apple Tools for Flipper (ATFf) - complete toolkit for working with iPhone! 🚀** 
