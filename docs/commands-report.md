# Звіт про використані Git-команди

| Команда                                    | Призначення                                                      |
|-------------------------------------------|------------------------------------------------------------------|
| `git init`                                | Ініціалізація локального репозиторію                              |
| `git config --global user.name "Ім'я"`    | Встановлення імені користувача                                    |
| `git config --global user.email you@ex.com` | Встановлення email                                              |
| `git checkout -b feature/one`             | Створення та перехід на нову гілку `feature/one`                  |
| `git commit -m "Повідомлення"`            | Фіксація змін у локальному репозиторії                            |
| `git remote add origin <URL>`             | Додавання віддаленого репозиторію                                 |
| `git push -u origin main`                 | Пуш гілки `main` на GitHub                                        |
| `git push -u origin feature/one`          | Пуш гілки `feature/one` на GitHub                                 |
| `git push origin --delete feature/two`    | Видалення гілки `feature/two` з GitHub                            |
| `git branch -d feature/two`               | Видалення локальної гілки `feature/two`                           |
