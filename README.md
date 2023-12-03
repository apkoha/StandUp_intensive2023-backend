# StandUp_intensive2023

- Интенсив my.methed.ru 21.11.2023.
- макет https://www.figma.com/file/S8tWzyFV28xy3RCHdgu0qV/Stand-Up-(Maraphone)
- серверная часть Node.js
- серверная часть развёрнута на https://glitch.com/
- запуск проекта после клонирования. api_stand-up - package.json - npm install, npm run start. Далее standup - package.json - npm install, dev vite --open.
- При ошибке plugin:vite:import-analysis] Failed to resolve import "fsevents" проверить нет ли main.js строки с импортами из vite, например: import { createFilter } from "vite";
