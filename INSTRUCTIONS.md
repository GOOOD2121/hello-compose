# Що робити далі

## 1. Відкрити проєкт

В Android Studio відкрийте папку `C:\Users\user\Desktop\Лабы\HelloCompose`.

## 2. Перевірити JDK

`File -> Settings -> Build, Execution, Deployment -> Build Tools -> Gradle -> Gradle JDK`

Виберіть `Embedded JDK 17`.

## 3. Дочекатися синхронізації

Після відкриття дочекайтесь `Gradle Sync`.

## 4. Запустити застосунок

Створіть емулятор у `Device Manager` або підключіть телефон, потім натисніть `Run`.

## 5. Зробити 2 скріншоти

Збережіть їх у папку `docs` під такими іменами:

- `app-screenshot-1.png`
- `app-screenshot-2.png`

## 6. Завантажити проєкт на GitHub

Команди:

```bash
git init
git add .
git commit -m "Initial commit: Hello Compose app"
git branch -M main
git remote add origin https://github.com/GO00D2121/hello-compose.git
git push -u origin main
git checkout -b develop
git push -u origin develop
git checkout -b feature/hello-compose
git push -u origin feature/hello-compose
```

## 7. Створити Issue і Pull Request

- Створіть один `Issue` через шаблон
- Створіть один `Pull Request` з `feature/hello-compose` у `develop`

## 8. Що відправити викладачу

- посилання на репозиторій
- посилання на README
- посилання на Issue
- посилання на Pull Request
- скріншот застосунку
- скріншот зеленого CI
