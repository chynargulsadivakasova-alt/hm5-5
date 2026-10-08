# product_cart — список карточек (React + props + SCSS modules)

Запуск:
```bash
npm install
npm run dev
```
Откройте адрес, который покажет Vite (обычно http://localhost:5173).

Структура:
- `src/data/products.js` — данные: массивы объектов
- `src/components/product_cart.jsx` — карточка, данные приходят через props
- `src/components/product_cart.module.scss` — изолированные стили (`product_cart`, `product_cart__*`)
- `src/App.jsx` — состояние (useState) и отрисовка списков через .map()
- `public/images` — картинки-заглушки; замените своими из Figma и в products.js поставьте IMG_EXT = 'jpg'
