# 🚪 Контроль Проходу — Система обліку персоналу

[![Live Demo](https://img.shields.io/badge/demo-online-green?style=for-the-badge)](https://carbon6600.github.io/tut/)
[![Firebase](https://img.shields.io/badge/firebase-realtime-orange?style=for-the-badge&logo=firebase)](https://firebase.google.com/)
[![PWA](https://img.shields.io/badge/PWA-ready-blue?style=for-the-badge)](https://web.dev/progressive-web-apps/)

<a href="https://carbon6600.github.io/tut/" target="_blank" rel="noopener noreferrer">
  <img width="485" height="727" alt="Знімок екрана 2026-02-17 203226" 
       src="https://github.com/user-attachments/assets/3198ceb5-2d91-4b85-81a3-e7d8837b4af1" />
</a>


> Мобільний веб-додаток для контролю проходу співробітників з реальним часом синхронізацією

🔗 **Жива демо:** https://carbon6600.github.io/tut/

---

## ✨ Функціонал

| Можливість | Опис |
|:-----------|:-----|
| 🔐 **PIN-авторизація** | 4-значний код з анімацією "рівня води" |
| 👥 **Ролі доступу** | Адміністратор / Редактор / Читач |
| 🏢 **8 статусів** | В приміщенні, ВЗ, РЗ, Обід, Нарада, Лікарня, Відрядження, Додому |
| ⚡ **Швидкі дії** | Миттєва зміна статусу з головного екрану |
| 📝 **Груповий вибір** | Масова зміна статусів |
| 📈 **Графік присутності** | Візуальний таймлайн (08:00-18:00) |
| 📊 **Статистика** | Підрахунок в реальному часі |
| 📤 **Експорт CSV** | Звіт за день |
| 🔄 **Realtime sync** | Firebase WebSocket |
| 📱 **PWA** | Встановлення на домашній екран |

---

## 🚀 Швидкий старт

### Перший запуск (Адміністратор)
Відкрити https://carbon6600.github.io/tut/
Ввести PIN: 1111
Створити користувачів у вкладці "⚙️ Адмін"
plain
Copy

### Ролі користувачів

| Роль | Можливості |
|:-----|:-----------|
| 🛡️ **Адмін** | Все + управління користувачами |
| ✏️ **Редактор** | Зміна статусів всіх співробітників |
| 👁️ **Читач** | Перегляд + зміна тільки свого статусу |

---

## 📱 Встановлення на телефон

**Android (Chrome):**
> ⋮ → "Додати на головний екран" → "Встановити"

**iOS (Safari):**
> ⎋ → "На екран «Додому»" → "Додати"

---

## 🛠️ Технології
Frontend:     Vanilla JS + CSS3 + HTML5
Database:     Firebase Realtime Database
Auth:         Firebase Anonymous + PIN
Hosting:      GitHub Pages
Sync:         WebSocket (Realtime)
plain
Copy

---

## 🔐 Безпека

> ⚠️ **Примітка:** Поточна версія використовує спрощені Firebase Rules. Для production:
> - [ ] Обмежити домени API ключа
> - [ ] Додати Firebase App Check
> - [ ] Серверна валідація прав

---

## 📝 Changelog

| Версія | Зміни |
|:-------|:------|
| `v1.3` | Виправлено UI, кнопка виходу, адаптивність |
| `v1.2` | Графік присутності, експорт CSV |
| `v1.1` | Система ролей (admin/editor/reader) |
| `v1.0` | Базова авторизація PIN, PWA |

---

## 📄 Ліцензія

MIT © 2026 Контроль Проходу
