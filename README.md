# Попади в Джем 🍸

3D-ходилка по ночному клубу: бегай по залу, собирай монеты, общайся с тусовщиками (NPC) и закупайся в баре.

Игра — один файл `index.html` (Three.js подгружается с CDN, поэтому при запуске нужен интернет).

## Управление

**Компьютер**
- `W` `A` `S` `D` — движение (камера от третьего лица, поворачивается за персонажем)
- `Пробел` — прыжок (двойной в воздухе)
- `Shift` — бег
- `E` — поговорить с NPC / открыть бар

**Телефон**
- Крестовина слева — ходьба
- `JUMP` — прыжок
- `E` — взаимодействие

## Как выложить на GitHub Pages

1. Создай новый репозиторий на GitHub (например `jam-club`).
2. Загрузи в него файлы `index.html` и `README.md`
   (кнопка **Add file → Upload files**, перетащи оба, затем **Commit changes**).
3. Открой вкладку **Settings → Pages**.
4. В разделе **Build and deployment** в поле **Source** выбери **Deploy from a branch**.
5. Branch: `main`, папка: `/ (root)` → **Save**.
6. Через 1–2 минуты обнови страницу — вверху появится ссылка вида
   `https://<твой-логin>.github.io/jam-club/`. Это и есть твой сайт.

### Через командную строку (по желанию)

```bash
git init
git add index.html README.md
git commit -m "Попади в Джем — 3D club game"
git branch -M main
git remote add origin https://github.com/<логин>/jam-club.git
git push -u origin main
```

Затем включи Pages в **Settings → Pages**, как описано выше.

## Свой домен (необязательно)

Купи домен у любого регистратора, добавь его в **Settings → Pages → Custom domain**
и пропиши в DNS записи, которые подскажет GitHub. HTTPS включается там же галочкой
**Enforce HTTPS**.
