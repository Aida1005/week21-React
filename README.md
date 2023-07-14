# week21-React
### Вопросы 💎

1. Обязательно ли скачивать и устанавливать какие-то библиотеки для начала работы с React?
   Не нужно ничего подключать или устанавливать.
   
2. Перечислите плюсы и минусы SPA приложений?
   Плюсы одностраничных web-приложени:

1.Возможность моментально получить доступ ко всем функциональным возможностям с любого девайса. Не нужно выяснять, совместимы ли устройства, какая у них предустановлена память, насколько высока производительность. Нет необходимости тратить время на инсталляцию софта.

2.Универсальное использование на устройствах с различными диагоналями и разрешениями экрана (если такая адаптивность учитывалась при разработке). Главное — иметь подключение к Интернету.

3.Можно передавать значительные объемы данных независимо от ограничений памяти используемого устройства.

4.Высокая производительность работы. Открытие одной страницы занимает гораздо меньше времени, к тому же не нужно постоянно загружать массивные объемы данных. Когда с сервера передаются новые модули, в SPA происходит лишь частичное обновление контента. Нет нужды опять загружать элементы, которые не изменились.

5.Широкие перспективы для разработчиков благодаря наличию фреймворков, которые содержат уже готовые рабочие компоненты. Создавать архитектуру проекта стало гораздо проще.

Минусы SPA:

1.Нужно всегда иметь подключение к Интернету. То есть такие программы никак нельзя использовать без сетевого доступа.

2.SEO-продвижение одностраничных веб-приложений крайне затруднено из-за принципов работы SPA. Поисковым системам индексировать модули приложения сложно, а порой просто невозможно. Соответственно, размещение такого софта на сайте может привести к проблемам с оптимизацией.

3.Если в устройствах отключена поддержка JavaScript, то одностраничные приложения просто не смогут функционировать.

4.Разработчики должны уделять особое внимание качеству своего софта, поскольку именно среди SPA часто встречаются откровенно слабые и сырые проекты.

3. Как создать React-приложение?
   npx create-react-app
   
4. Является ли React фреймворком?
   React считается библиотекой пользовательского интерфейса.
   А какие ещё есть веб-фронтенд фреймворки?
Angular.js
Vue.js
Ember.js
jQuery
   
5. Какой командой можно добавить библиотеку или компонент в свой файл?
   Для установки библиотеки в проект используется команда npm install [package - name] import используем для добавления библиотеки или компонента в файл (import { Chart } from "react-google-charts");
6. Найдите три внешних React-компонента, которые вам могут пригодиться в будущем (*например, react-color, react-google-maps и пр.*)
7. Какой основной файл SPA-проекта, где мы делаем изменения?
    App.js
8. Зачем нужна папка build и какой командой мы генерируем её содержимое?
   Команда build позволяет сгенерировать файл сборки, и затем этот файл может использоваться в production (Команда npm run build).
