### **В нашем проекте мы приняли решение использовать git flow. Данный файл будет содержать материалы для изучения и их переосмысление в текст.**

## Видео
- [Стратегии Бранчевания GIT FLOW. Просто о сложном.](https://www.youtube.com/watch?v=bo9Alwd_Ndk)
- [Git, Git Flow, TDD #1 - Что нужно знать о работе с Git](https://www.youtube.com/watch?v=9iWVaJpeDA8)
- [Git, Git Flow, TDD #2 - Git Flow: Основы работы с ветками в Git](https://www.youtube.com/watch?v=wGJQWnmlSpc)
- [Git, Git Flow, TDD #3 - Введение в TDD и тестирование в Python](https://www.youtube.com/watch?v=ptssYZR4kus)

## Итоги видео

Существует 2 основые ветки:
- **main** (самый последний релиз)
- **develop** (рабочая ветка в которую мержат все фичи)

Также существует 3 типа веток:
-  **feature** (тобеж фичи, в нашем случае - таски)
1. Создаются от **develop**
2. Мержатся в **develop**
3. Название исходят от таски
- **release** (тобеж релизы)
1. Создаются от **develop**
2. Мержатся в **main**
3. Названия состоят из release-* (к примеру release-0.1)
- **Hot-Fix** (фикс багов и тп)
1. Создаются от **main** или **develop**
2. Мержатся в **develop** и **main**
3. Названия состоят из hotfix-* (к примеру hotfix-0.1.1)

#### **[Картинка для примера](https://expressus.io/uploads/beautiful-gitflow-workflow-diagram.png)**