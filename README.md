# template_django
Template for django start project


1. Обрати розміщення для теки
   -
   
      `D:` - Перейти на обраний диск
   
      `cd - <розміщення/назва теки>` - зайти до директорії

      `cd..` - Вийти до попередньої директорії 
   
      `dir` - Показати вміст поточної теки

2. Створити теку
   ```bash
   md "Назва_теки"
   ```

3. Клонувати
   ```bash
   git clone "<https://github.com/n1xford/template_django.git>"
   ```

4. Віртуальне середовище
   - Створити віртуальне середовище `.venv` або підключити існуюче
       ```bash
     #створення віртуального середовища
      python -m venv .venv
      ```
   - Активація віртуального середовища
   ```bash
    # Windows
    .venv\Scripts\activate
    
    # Linux & MacOS
    .venv\bin\activate
    ```

5. Встановлення необхідних модулей
   ```bash
   pip install requaest.txt
   ```
   
6. Створення нового проєкту Django

