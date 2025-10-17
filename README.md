# 🧪 Лабораторная работа №4: CSS-библиотеки

## 📘 Тема
Работа с CSS-библиотеками — создание лендингов с использованием **Bootstrap** и **Tailwind CSS**.

---

## 💻 Лендинг на Bootstrap
*(место под скрины)*

---

## 💻 Лендинг на Tailwind
*(место под скрины)*

---

## 🧩 Ответы на вопросы

### 1️⃣ Какой подход (компонентный Bootstrap или utility-first Tailwind) показался вам удобнее для этой задачи и почему?

**Bootstrap** показался мне удобнее, так как он предоставляет уже готовые, комплексные стили.  
Однако он неудобен, когда требуется более гибкая стилизация страницы — в этом случае приходится изменять компоненты библиотеки или использовать стандартный CSS.  

**Tailwind**, в свою очередь, удобен, когда необходима гибкость в стилизации.  
Но код с его использованием получается громоздким и менее читаемым.  
Tailwind не очень подходит для небольших проектов.

---

### 2️⃣ Пример кода для одного и того же элемента (например, навигации) на Bootstrap и на Tailwind

#### 🟦 Bootstrap
```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">AI Assistant Pro</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#hero">Главная</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">О продукте</a></li>
        <li class="nav-item"><a class="nav-link" href="#features">Преимущества</a></li>
        <li class="nav-item"><a class="nav-link" href="#footer">Контакты</a></li>
      </ul>
    </div>
  </div>
</nav>
