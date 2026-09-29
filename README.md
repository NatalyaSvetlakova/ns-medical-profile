<div align="center">

# 🩺 Медицинские сертификаты

**Персональная онлайн-галерея сертификатов и удостоверений о повышении квалификации**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-0e6ba8?style=for-the-badge&logo=github)](https://NatalyaSvetlakova.github.io/medical-certificates/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/ru/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/ru/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/ru/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/license-Personal-lightgrey?style=for-the-badge)](#-лицензия)

[**🌐 Открыть галерею**](https://NatalyaSvetlakova.github.io/medical-certificates/) · [**🐛 Сообщить о проблеме**](https://github.com/NatalyaSvetlakova/medical-certificates/issues)

</div>

---

## 📸 Скриншот

<table>
  <tr>
    <td align="center">
      <img src="docs/light.jpg" width="400" alt="Светлая тема"><br>
      <sub><b>Светлая тема</b></sub>
    </td>
    <td align="center">
      <img src="docs/dark.jpg" width="400" alt="Тёмная тема"><br>
      <sub><b>Тёмная тема</b></sub>
    </td>
  </tr>
</table>

---

## 📖 О проекте

Персональная онлайн-галерея сертификатов и удостоверений о повышении квалификации. Файлы хранятся в репозитории, а страница автоматически подгружает их через GitHub API — **новые сертификаты появляются на сайте без правки кода**.

Страница выдержана в медицинской палитре: глубокий синий, бирюзовый акцент, сине-серые плашки. Поддерживает светлую и тёмную темы автоматически.

---

## ✨ Возможности

| | Возможность | Описание |
|---|---|---|
| 🔄 | **Автоподгрузка** | Файлы читаются из папки `certificates/` через GitHub API. Добавили файл → он сразу на сайте. |
| 🖼 | **Поддержка форматов** | JPG, JPEG, PNG, WebP, GIF, JFIF, BMP и PDF. |
| 📄 | **PDF-превью** | Первая страница PDF рендерится в миниатюру через PDF.js. |
| ⚡ | **Ленивая загрузка** | Превью PDF строятся только когда карточка попадает в поле зрения. |
| ⏱ | **Часы обучения** | Для каждого сертификата можно указать объём программы. |
| 🌗 | **Тёмная / светлая тема** | Автоматически по системным настройкам. |
| 📱 | **Адаптивность** | 3 колонки на десктопе, 2 на планшете, 1 на телефоне. |
| 🗓 | **Сортировка по дате** | Новые сертификаты — сверху. |
| 🇷🇺 | **Русские названия и метаданные** | Задаются через словари `TITLES`, `META`, `HOURS`. |

---

## 🗂 Структура проекта
medical-certificates/
├── index.html          (страница сертификатов)
├── articles.html       (новая страница статей)
├── articles.json       (данные статей)
├── sitemap.xml
└── certificates/       (папка с файлами сертификатов)


---

## 🚀 Быстрый старт

### Клонирование репозитория

```bash
git clone https://github.com/NatalyaSvetlakova/medical-certificates.git
cd medical-certificates