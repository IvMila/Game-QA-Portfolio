### **01\. Змішання мов** 

**ID:** BUG\_001  
**Title:** Змішана локалізація (система vs мова гри)  
**Date:** 05.06.25  
**Version:** 3.5.4 (1514)

**Description:** Деякий текст не перекладається між системною мовою та мовою у грі

**Steps to Reproduce:**

1. У телефоні відкрити налаштування \- програми \- Dancing Line \- мова \- (наприклад \- англійська)  
2. Відкрити гру, застосувати мову у налаштуваннях \- (наприклад \- українська)  
3. Звернути увагу на інтерфейс у вкладці “Досягнення”

**Expected result:** 

* весь текст у гри відображається мовою гри незалежно від мови системи  
* випадків змішаних мов (англ/укр) бути не повинно


**Actual result:**

* частина тексту (наприклад: "The Spring Lullaby", "Spring", "Complete The Spring") залишаються англійською, незважаючи на обрану українську мову в налаштуваннях гри.


**Type of bug:** Localization   
**Severity:** Major  
**Priority:** High  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**   
<img width="250" height="500" alt="1" src="https://github.com/user-attachments/assets/e003b573-9373-411b-8901-03fe0d5c8951" /> <img width="250" height="500" alt="2" src="https://github.com/user-attachments/assets/4dc032c2-34f6-45e5-ac70-6b2e4fe6c08f" /> <img width="250" height="500" alt="3" src="https://github.com/user-attachments/assets/f06acca6-859c-4b36-bf3a-11386d7e136c" />


**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open

### **02\. Звук відтворюється ЛИШЕ через навушники**

**ID:** BUG\_002  
**Title:** Звук у грі не програється через динамік  
**Date:** 05.06.25  
**Version:** 3.5.4 (1514)

**Description:** Запустивши гру з підключеними наушниками \- звук відтворюється коректно, але  якщо навушники НЕ підключені \- звук гри не відтворюється. Це обмежує доступ до гри для користувачів без навушників і негативно впливає на ігровий досвід.  

**Steps to Reproduce:**

1. Запустити гру з навушниками → звук є  
2. Запустити гру без навушників → звуку немає.  
   

**Expected result:** 

* звук відтворюється незалежно від типу вихідного пристрою


**Actual result:**

* звук гри відтворюється лише у навушниках, через динамік телефону звук не відтворюється 


**Type of bug:** Functional   
**Severity:** Critical  
**Priority:** High

**Environment:** iPhone 16, iOS 18.3.1  
**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open

### **03\. Некоректне вирівнювання та розмір тексту в українській локалізації**

**ID:** BUG\_003  
**Title:** Некоректний розмір/вирівнювання тексту у вкладці каменів  
**Date:** 05.06.25  
**Version:** 3.5.4 (1514)

**Description:** У вкладці з дорогоцінними каменями текст в українській локалізації “Щоденні безкоштовні дорогоцінні камені” нечитабельний через малий розмір та некоректне вирівнювання

**Steps to Reproduce:**

1. На головному екрані гри натиснути на вкладку (див. на верхню частину) з дорогоцінними каменям.  
2. Звернути увагу на текст з “Щоденні безкоштовні дорогоцінні камені”  
   

**Expected result:** 

* весь текст інтерфейсу коректно відображає \- розмір, розміщення, вирівнювання тощо


**Actual result:**

* текст відображається некоректно, занадто малий щоб бути читабельним 


**Type of bug:** UI   
**Severity:** Major  
**Priority:** Medium  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**   
<img width="250" height="500" alt="4" src="https://github.com/user-attachments/assets/0b16a8de-19e7-428e-a5fc-843fcd2a6b4b" />

**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open

### **04\. У головному меню візуалізація рівня “Весняна Колискова” деякі об'єкти вібрують/смикаються**

**ID:** BUG\_004  
**Title:** Об'єкти на візуалізації з головного меню "Весняна Колискова" вібрують  
**Date:** 06.06.25  
**Version:** 3.5.4 (1514)

**Description:** Візуалізація “Весняна Колискова” деякі об'єкти вібрують/смикаються, як ніби взаємодіють через конфлікт фізики

**Steps to Reproduce:**

1. Знаходитися на головному екрані гри  
2. На головному екрані двічі свайпнути або натиснути “стрілку вправо” для переходу до рівня “Весняна Колискова”  
3. Звернути увагу на об’єкти які вібрують  
   

**Expected result:** 

* всі об'єкти мають бути стабільно зафіксовані 

**Actual result:**

* деякі об’єкти поводять себе некоректно, що псує враження гравця  


**Type of bug:** UI / Visual / Physics  
**Severity:** Low  
**Priority:** Low  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**   
<img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/2e56deee-a216-4971-a738-55be0f3f93ec" />

**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open

### **05\. Некоректне розміщення тексту (назва гри при першому запуску)** 

**ID:** BUG\_005  
**Title:** Некоректне розміщення тексту (назва гри при першому запуску)  
**Date:** 06.06.25  
**Version:** 3.5.4 (1514)

**Description:** Після завершення ознайомчого рівня на головному екрані гри з'являється назва "Dancing Line", яка частково виходить за межі екрану.

**Steps to Reproduce:**

1. Відкрити гру  
2. Завершити ознайомчий рівень  
3. Звернути увагу на анімаційний текст з назвою гри  
   

**Expected result:** 

* текст повністю у видимій області, не виходить за межі незалежно від розміру екрана, зберігає візуальний баланс


**Actual result:**

* частина тексту “Dancing Line” виходить за межі екрана зліва, порушуючи візуальний баланс головного екрана


**Type of bug:** UI / Visual   
**Severity:** Medium  
**Priority:** Low  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**   
<img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/e123ffb2-6eef-4d9d-81b2-ac75b528d425" />

**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open 

### **06\. Зникнення підказки маршруту**

**ID:** BUG\_006  
**Title:** Підказка маршруту зникає майже одразу  
**Date:** 07.06.25  
**Version:** 3.5.4 (1514)

**Description:** Підказка зникає після купівлі на всіх платних рівнях 

**Steps to Reproduce:**

1. Знаходитися на платні пісні  
2. Натиснути на кнопку “відкрити безкоштовно” (перегляд реклами)  
3. Розпочати пробний рівень (тапнути для старту)   
4. Купити підказку маршруту  
5. Підтвердити початок гри (тапнути знову)  
6. Перевірити наявність підказки під час гри    
   

**Expected result:** 

* підказка маршруту активна та проводить гравця до самого кінця рівня 


**Actual result:**

* підказка не проводить гравця до кінця рівня у всіх платних мелодіях


**Type of bug:** UI / Gameplay / Functional  
**Severity:** Medium  
**Priority:** Medium  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**  
<img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/58c94000-ebd5-4ed6-be98-baafad59e40b" /> <img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/8d20001c-65b3-4d73-9294-a7db8ead8c10" /> <img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/6c11abe8-58eb-4d26-adc4-5b475c917eb7" /> <img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/a1cec78a-caa5-480b-9671-c43fae7bba4a" /> 


**Environment:** iPhone 16, iOS 18.3.1  
**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open 

### **07\. Прогрес не зберігається при різкому виході під час гри** 

**ID:** BUG\_007  
**Title:** Прогрес рівня не зберігається при різкому виході  
**Date:** 07.06.25  
**Version:** 3.5.4 (1514)

**Description:** Під час проходження рівня гра не зберігає дані при різкому згортанні програми 

**Steps to Reproduce:**

1. Звернути увагу на прогрес рівня  
2. Розпочати будь який рівень (тапнути на екран)  
3. Різко закрити гру (свайпнути з багатозадачності)  
4. Відкрити гру знову  
5. Перевірити, чи збережено прогрес  
   

**Expected result:** 

* прогрес зберігається і гравець може продовжити з того ж моменту, UI прогресу оновлюється та демонструє на скільки % рівень пройдено


**Actual result:**

* прогрес не зберігається, рівень доводиться проходити заново


**Type of bug:** Gameplay / Functional  
**Severity:** Medium  
**Priority:** Medium  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**  
 <img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/eb5ef52d-cede-4010-9547-9178474c721e" /> <img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/d0ba3efd-a9f6-4813-9ae5-5d644e54b5fa" /> <img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/dbffcc03-7bd8-4115-a93f-25076b7a1494" /> <img width="250" height="500" alt="13" src="https://github.com/user-attachments/assets/61e3481c-0d28-4fff-af71-a80d0ffa6811" /> <img width="250" height="500" alt="5" src="https://github.com/user-attachments/assets/887aa902-ba67-4f9b-93a9-86d06acab4fd" /> 

**Environment:** iPhone 16, iOS 18.3.1  
**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open 

### **08\. Розмір ігрового об'єкту малий на рівні “The Beach”**

**ID:** BUG\_008  
**Title:** \[Non-reproducible\] Розмір ігрового об’єкту (куб) став малим на рівні “The Beach”  
**Date:** 07.06.25  
**Version:** 3.5.4 (1514)

**Description:** Куб одного разу з’явився значно меншим від очікуваного на початку рівня “The Beach”. Повторити помилку не вдалося

**Steps to Reproduce:**  
Проблема виникла лише один раз, точна послідовність дій невідома. Орієнтовні умови, коли було помічено:

1. Почати рівень “The Beach”  
2. Звернути увагу на ігровий об’єкт  
   

**Expected result:** 

* ігровий об’єкт (куб) має стандартний розмір


**Actual result:**

* куб відображався у зменшеному розмірі


**Type of bug:** Graphics / Visual  
**Severity:**  Medium  
**Priority:** Low  
**Reproducibility:** Rare / Could not reproduce (1/5 спроб)  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**  
<img width="250" height="500" alt="17" src="https://github.com/user-attachments/assets/6a3ad78c-6da6-4520-a60b-8da3765e6625" /> <img width="250" height="500" alt="17" src="https://github.com/user-attachments/assets/2a1a8dc3-2093-4d5d-9889-e769511bd122" />


**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open 

### **09\. Ігрова локація не завантажується на рівні “The Plains”** 

**ID:** BUG\_009  
**Title:** Зникнення ігрової сцени на рівні “The Plains”   
**Date:** 08.06.25  
**Version:** 3.5.4 (1514)

**Description:** Почавши рівень “The Plains” приблизно через 3 секунди було помічено що ігрова сцена не завантажується

**Steps to Reproduce:**

1. Знайти рівень “The Plains” (скролити у головному меню)  
2. Розпочати рівень (натиснувши на перегляд реклами)  
3. Знову тапнути для старту  
4. Звернути увагу що рівень різко закінчується завантажуватися  
   

**Expected result:** 

* всі рівні мають бути коректно завантаженими та доступними для гравця


**Actual result:**

* ігровий рівень (сцена) пустий/а, зникає  
* пройти успішно рівень нереально


**Type of bug:** Gameplay / Functional  
**Severity:** Medium  
**Priority:** Medium  
**Environment:** iPhone 16, iOS 18.3.1  
**Attachment:**  
<img width="250" height="500" alt="17" src="https://github.com/user-attachments/assets/617bcd4d-2c4a-4eeb-adf8-e17a78571f06" /> <img width="250" height="500" alt="18" src="https://github.com/user-attachments/assets/a598adad-b6e5-4102-9d95-4e87b26143d7" />


**Reporter:** Mila  
**Assigned to:** dev  
**Status**: open  


