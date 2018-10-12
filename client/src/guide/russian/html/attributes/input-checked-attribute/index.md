---
title: Input Checked Attribute
localeTitle: Введенный атрибут ввода
---
## Введенный атрибут ввода

Проверенный атрибут является логическим атрибутом.

Когда он присутствует, он указывает, что  элемент должен быть предварительно выбран (отмечен) при загрузке страницы.

Проверенный атрибут может использоваться с  а также  ,

Проверенный атрибут также можно установить после загрузки страницы с помощью JavaScript.

## Взгляните на следующий пример:

```html

<form action="/action_page.php"> 
  <input type="checkbox" name="vehicle" value="Bike"> I have a bike<br> 
  <input type="checkbox" name="vehicle" value="Car" checked> I have a car<br> 
  <input type="submit" value="Submit"> 
 </form> 
```

В приведенном выше примере, когда веб-страница загружается по умолчанию, первый флажок автоматически выбирается из-за атрибута checked.