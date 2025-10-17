# 🧪 Лабораторная работа №4: CSS-библиотеки

## 📘 Тема
Работа с CSS-библиотеками — создание лендингов с использованием **Bootstrap** и **Tailwind CSS**.

---

## 💻 Лендинг на Bootstrap
*(место под скрины)*
<img width="2542" height="1348" alt="image" src="https://github.com/user-attachments/assets/5a93703d-e13a-4923-a573-21de789d08b3" />
<img width="2543" height="1350" alt="image" src="https://github.com/user-attachments/assets/e48e94ad-6859-47d8-b363-0c1159fa5b1d" />
<img width="2526" height="1337" alt="image" src="https://github.com/user-attachments/assets/c1643eee-2ab0-4e71-8cde-5517eb2d9dde" />
<img width="2538" height="1350" alt="image" src="https://github.com/user-attachments/assets/9002c294-f5af-4593-a8e4-12355180f6b7" />



## 💻 Лендинг на Tailwind
<img width="2535" height="1348" alt="image" src="https://github.com/user-attachments/assets/6c9405fa-b292-4d99-8936-f35dd9ef26b2" />
<img width="2538" height="1345" alt="image" src="https://github.com/user-attachments/assets/fe85fb4f-5aa1-47a8-8821-c53117cfb40c" />
<img width="2519" height="1341" alt="image" src="https://github.com/user-attachments/assets/1d82258f-3a60-4d8e-a35c-b59dc69d5375" />
<img width="2526" height="1349" alt="image" src="https://github.com/user-attachments/assets/676b3dba-2005-4ebe-9c6e-ffc568146493" />


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
