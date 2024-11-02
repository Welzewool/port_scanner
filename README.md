# 🕵️‍♂️ Port Scanner

Сканер портов — это инструмент, который позволяет проверить, какие порты открыты на заданном хосте. Этот проект предназначен для изучения основ работы с сокетами в Python и помогает выявить активные порты на сервере.

## 🚀 Установка

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/Welzewool/test_1.git
   ```

2. Перейдите в папку проекта:
   ```bash
   cd test_1
   ```

3. Создайте и активируйте виртуальное окружение:
   ```bash
   python -m venv venv  # Создание виртуального окружения
   source venv/bin/activate  # Активация на macOS/Linux
   venv\Scripts\activate  # Активация на Windows
   ```

4. Установите необходимые зависимости (если они есть):
   ```bash
   pip install -r requirements.txt
   ```

## 📜 Использование

Запустите сканер, используя команду:

```bash
python3 main.py
```

Вводите имя сайта (без `http`/`https`) или IP-адрес для сканирования портов.

### Пример

```
Введи имя сайта без http/https или IP-адрес: example.com
Ожидайте, идет сканирование портов!
example.com: 22 порт активен
example.com: 80 порт активен
Сканирование завершено
```

## 🔧 Возможности

- Сканирование заданного списка портов.
- Определение открытых портов с указанием активного состояния.

## ⚙️ Технологии

- Python
- Модуль `socket`
- Dataclasses

## 📄 Лицензия

Этот проект лицензирован на условиях MIT License. Пожалуйста, ознакомьтесь с файлом [LICENSE](LICENSE) для получения подробной информации.

## 📬 Контакты

Если у вас есть вопросы или предложения, свяжитесь со мной через GitHub: [Welzewool](https://github.com/Welzewool).

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Welzewool&show_icons=true&hide_title=true&count_private=true&theme=radical)
