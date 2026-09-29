# image-to-dxf
Скрипт для конвертации изображений и PDF-файлов в формат DXF (AutoCAD)
Markdown
# Image / PDF to DXF Converter

Простой инструмент на Python для автоматической конвертации изображений (PNG, JPG) и PDF-файлов в формат **DXF**, используемый в AutoCAD и других САПР-системах.

---

## 📁 Структура проекта

```text
image_to_dxf/
├── image_to_dxf.py    # Основной скрипт конвертации
└── run.bat            # Скрипт быстрого запуска для Windows
🚀 Быстрый старт
Требования
Убедитесь, что у вас установлен Python 3.8+.

Установите необходимые зависимости (если используются библиотеки OpenCV, ezdxf, Pillow или pdf2image):

Bash
pip install ezdxf opencv-python pillow pdf2image
Примечание: Если вы используете pdf2image, убедитесь, что в системе установлен Poppler.

🛠️ Использование
Запуск через BAT-файл (Windows)
Просто запустите файл run.bat двойным кликом.

Запуск через консоль
Bash
python image_to_dxf/image_to_dxf.py
📝 Лицензия
Проект распространяется под лицензией MIT.


---

### 3. Инструкция по загрузке файлов через Git

Если вы загружаете проект через командную строку, выполните в папке с проектом следующие команды:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/IgorBelioglo/image-to-dxf.git
git push -u origin main
