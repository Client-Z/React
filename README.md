# BSA-8-React / Part 1

## Задание:

Создать компонент, который будет оперировать списком пользователей. Компонент должен содержать 2 дочерних компонента: Компонент для добавления пользователей Компонент для отображения списка пользователей Компонент для отображения информации об одном пользователе

Компонент для добавления пользователей должен содержать поле для ввода имени и кнопку “Добавить”. Для обработки действия кнопки передайте в данный компонент функцию-обработчик из родительского компонента, для того, чтобы вы смогли сохранить добавляемого пользователя в состоянии главного компонента.

Объект пользователя содержит только имя и уникальный идентификатор.

Компонент для отображения списка пользователей в свою очередь содержит массив компонентов, которые отвечают за отображение добавленных пользователей. Компонент для отображения информации об одном пользователе в списке содержит имя пользователя и кнопку удаления. Функция-обработчик удаления аналогично компоненту для добавления пользователей должна быть передана из родительского компонента, как и список пользователей для отображения.

Использовать где необходимо:

props для передачи функций;

state для текущего состояния отображения;

Правильно использовать атрибут key для списка;

shouldComponentUpdate;

Event handling;

P.S. Не забудьте хоть о каких-то стилях, чтоб было понятно где что.

---   

1. Git clone
2. npm i
3. npm start
4. Go to localhost:3000/