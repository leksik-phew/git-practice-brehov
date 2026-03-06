# Git Practice – Brehov

## Описание проекта

Этот репозиторий создан для практики работы с **Git и GitHub workflow**.
Цель проекта — освоить основные инструменты совместной разработки:

* создание **Issues**
* работа с **ветками (branches)**
* создание **Pull Request**
* оформление **документации**

Проект используется как тренировочная среда для изучения Git.

---

## Установка

1. Клонируйте репозиторий:

```bash
git clone https://github.com/leksik-phew/git-practice-brehov.git
```

2. Перейдите в папку проекта:

```bash
cd git-practice-brehov
```

3. Убедитесь, что Git установлен:

```bash
git --version
```

---

## Использование

Основной workflow работы с проектом:

1. Создать новую ветку для задачи:

```bash
git checkout -b feature/your-feature-name
```

2. Внести изменения в файлы проекта.

3. Добавить изменения:

```bash
git add .
```

4. Сделать commit:

```bash
git commit -m "feat: add new feature"
```

5. Отправить ветку в GitHub:

```bash
git push origin feature/your-feature-name
```

6. Создать **Pull Request** в GitHub.

---

## Работа через Pull Request

Работа в проекте выполняется через **ветки и Pull Request**.

Основной процесс:

1. Создать Issue для задачи
2. Создать отдельную ветку
3. Внести изменения
4. Сделать commit
5. Отправить ветку на GitHub
6. Создать Pull Request
7. После проверки выполнить merge

---

## Документация

Дополнительные материалы находятся в папке:

```
notes/
```

Например:

* `notes/git-basics.md` — основные команды Git
* описание работы с ветками
* объяснение Pull Request

---

## Автор

GitHub:
https://github.com/leksik-phew
