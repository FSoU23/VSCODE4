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
<!-- Из hero-section -->
<button class="btn btn-primary btn-lg">Начать бесплатно</button>

<!-- Из pricing section -->
<button class="btn btn-outline-light">Выбрать план</button>
<button class="btn btn-light">Популярный выбор</button>

#### 🟦 Tailwind
```html
<!-- Из hero-section -->
<button class="bg-highlight hover:bg-cyan-500 text-white font-bold py-4 px-10 rounded-full text-lg transition-all transform hover:scale-105 hover:shadow-2xl">
    Начать бесплатно
</button>

<!-- Из pricing section -->
<button class="w-full border-2 border-gray-300 hover:border-highlight text-gray-300 hover:text-highlight font-bold py-3 rounded-lg transition-all">
    Приобрести
</button>
<button class="w-full bg-white text-highlight font-bold py-3 rounded-lg hover:bg-gray-100 transition-all">
    Приобрести
</button>

