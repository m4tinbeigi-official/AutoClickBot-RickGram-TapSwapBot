<!-- DevSponsors Badges -->
<p align="center">
  <a href="https://devsponsors.github.io"><img src="https://img.shields.io/badge/DevSponsors-Verified_OSS-6366f1?style=for-the-badge&logo=github" alt="DevSponsors Verified"></a>
  <a href="https://devsponsors.github.io"><img src="https://img.shields.io/badge/Sponsor-DevSponsors_Hub-emerald?style=for-the-badge&logo=github-sponsors" alt="DevSponsors Sponsor"></a>
  <a href="https://devsponsors.github.io/mediakit.html"><img src="https://img.shields.io/badge/Infrastructure-DevSponsors_Cloud-ec4899?style=for-the-badge&logo=server" alt="DevSponsors Cloud"></a>
</p>

[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/hidden_coding)

![image psd(13)](https://github.com/AlexKrutoy/TapSwapBot/assets/73156836/db444c1d-f3ba-47cb-bea7-e8b85f7cd03d)


![img1](.github/images/demo.png)

## Recommendation before usage

# 🔥🔥 use PYTHON 3.10 🔥🔥

> 🇪🇳 README in english available [here](README-EN.md)

## Функционал  
| Функционал                                                     | Поддерживается  |
|----------------------------------------------------------------|:---------------:|
| Многопоточность                                                |        ✅        |
| Привязка прокси к сессии                                       |        ✅        |
| Авто-покупка предметов при наличии монет (tap, energy, charge) |        ✅        |
| Рандомное время сна между кликами                              |        ✅        |
| Рандомное количество кликов за запрос                          |        ✅        |
| Поддержка tdata / pyrogram .session / telethon .session        |        ✅        |


## [Настройки](https://github.com/AlexKrutoy/TapSwapBot/blob/main/.env-example)
| Настройка                | Описание                                                                                    |
|--------------------------|---------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**    | Данные платформы, с которой запускать сессию Telegram (сток - Android)                      |
| **MIN_AVAILABLE_ENERGY** | Минимальное количество доступной энергии, при достижении которой                            |
|                          | будет задержка (напр. [10, 100])                                                            |                                   
| **SLEEP_BY_MIN_ENERGY**  | Задержка при достижении минимальной энергии в секундах (напр. [40,200])                     |
| **ADD_TAPS_ON_TURBO**    | Сколько тапов будет добавлено при активации турбо (напр. 2500)                              |
| **AUTO_UPGRADE_TAP**     | Улучшать ли тап (True / False)                                                              |
| **MAX_TAP_LEVEL**        | Максимальный уровень прокачки тапа (до 20)                                                  |
| **AUTO_UPGRADE_ENERGY**  | Улучшать ли энергию (True / False)                                                          |
| **MAX_ENERGY_LEVEL**     | Максимальный уровень прокачки энергии (до 20)                                               |
| **AUTO_UPGRADE_CHARGE**  | Улучшать ли заряд энергии (True / False)                                                    |
| **MAX_CHARGE_LEVEL**     | Максимальный уровень прокачки заряда энергии (до 5)                                         |
| **APPLY_DAILY_ENERGY**   | Использовать ли ежедневный бесплатный буст энергии (True / False)                           |
| **APPLY_DAILY_TURBO**    | Использовать ли ежедневный бесплатный буст турбо (True / False)                             |
| **RANDOM_CLICKS_COUNT**  | Рандомное количество тапов (напр. [50,200])                                                 |
| **SLEEP_BETWEEN_TAP**    | Рандомная задержка между тапами в секундах (напр. [10,25])                                  |
| **USE_PROXY_FROM_FILE**  | Использовать-ли прокси из файла `bot/config/proxies.txt` (True / False)                     |

## Быстрый старт 📚
1. Чтобы установить библиотеки в Windows, запустите INSTALL.bat.
2. Для запуска бота используйте `START.bat` (или в консоли: `python main.py`).

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/AlexKrutoy/TapSwapBot) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/AlexKrutoy/TapSwapBot.git
cd TapSwapBot
```

# Linux
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

# Windows
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/TapSwapBot >>> python3 main.py --action (1/2)
# Или
~/TapSwapBot >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


Спасибо за идею:
[<img src="https://img.shields.io/badge/Telegram-%40shamhi-orange">](https://t.me/sho6ot)



### Контакты

Для поддержки или вопросов, свяжитесь со мной в Telegram: [@hidden_coding](https://t.me/hidden_coding)
