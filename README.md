# mgml-form
Сайт позволяет удобно заполнить все необходимые данные для оформления стимулирующих выплат и автоматически генерирует готовый PDF документ по установленному шаблону

### Как работает код в целом:

1. **Структура приложения**:
   - `index.html` - основной файл с разметкой формы
   - `style.css` - стили для адаптивного отображения формы
   - `main.js` - основная логика работы с формой (добавление/удаление условий и приложений)
   - `validation.js` - валидация вводимых данных
   - `pdf-generator.js` - генерация PDF документа на основе введенных данных

2. **Основной функционал**:
   - Пользователь заполняет форму с ФИО, должностью
   - Добавляет условия выплат с указанием пункта, примечания и суммы
   - Может прописывать приложения к форме
   - Все поля валидируются в реальном времени
   - При нажатии на кнопку "Сформировать" проверяется корректность всех данных
   - Генерируется PDF документ с заполненными данными

3. **Ключевые особенности**:
   - Адаптивный дизайн для мобильных устройств
   - Валидация всех полей формы
   - Динамическое добавление/удаление условий и приложений
   - Форматирование ввода сумм (разделение тысяч пробелами)
   - Генерация PDF с табличной структурой
   - Защита от двойного нажатия при генерации PDF
   - Разное поведение на мобильных и десктоп устройствах (скачивание/открытие PDF)

4. **Технологии**:
   - HTML5, CSS3, JavaScript (ES6)
   - Библиотека pdfMake для генерации PDF
   - Адаптивная верстка с медиазапросами
   - Регулярные выражения для валидации
