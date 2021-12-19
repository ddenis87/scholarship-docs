# Документ расчетов

## Форма элемента
<b>Компонент:</b> ElementDocumentcalculation

#### Входные параметры:
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|element|Значения полей формы|`Object|null`|`false`|`{ id: -1 }`|
|options|Поля формы|`Object`|`true`|`{}`|
|name|Имя формы|`String`|`true`|`null`|

#### События
|Event Name|Description|Parameters|
|---|---|---|
|accept|Запись/изменения формы|`fieldsValue: {}`|
|close|Закрытие формы|-|

## Форма списка
<b>Компонент:</b> ListDocumentcalculation

#### Входные параметры:
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|defaultOptions|Опции таблицы|`Object`|`false`|`{}`|
|defaultFilters|Фильтры таблицы|`Object`|`false`|`{}`|
|typeRowNumber|Тип строки|`Number`|`false`|`0`|
|typeColumn|Тип колонки|`String`|`true`|`fixed`|
|isAdding|Режим добавления|`Boolean`|`false`|`true`|
|isAddingForm|Режим добавления в форме|`Boolean`|`false`|`true`|
|isAddingInline|Режим добавления в строке|`Boolean`|`false`|`true`|
|isEditable|Режим редактирования|`Boolean`|`false`|`true`|
|isEditableForm|Режим редактирования в форме|`Boolean`|`false`|`true`|
|isEditableInline|Режим редактирования в строке|`Boolean`|`false`|`true`|
|isFooter|Отображение подвала|`Boolean`|`false`|`false`|
|isExpansion|Режим раскрытия строк|`Boolean`|`false`|`false`|
|isMultiline|Многострочный режим|`Boolean`|`false`|`false`|
|isHierarchy|Иерарический режим|`Boolean`|`false`|`true`|

#### События
|Event Name|Description|Parameters|
|---|---|---|
|blur:table|Потеря фокуса таблицей|-|
|editing:element|Редактирование элемента|`options: {}`|
|focused:element|Сфокусирован элемент таблицы|`element: {}`|
|mounted:table|Таблица смонтирована на страницу|`optionsTable: {}`|
|selected:element|Выбор элемента (двойной клик)|`element: {}`|

## Табличные части
___1. Расчеты___

<b>Компонент:</b> Tabledocumentcalculation

___2. Корректировки показателей___

<b>Компонент:</b> Tabledocumentcalculationcorrectionindicator

#### Входные параметры:
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|defaultOptions|Опции таблицы|`Object`|`false`|`{}`|
|defaultFilters|Фильтры таблицы|`Object`|`false`|`{}`|
|typeRowNumber|Тип строки|`Number`|`false`|`0`|
|typeColumn|Тип колонки|`String`|`true`|`fixed`|
|isAdding|Режим добавления|`Boolean`|`false`|`true`|
|isAddingForm|Режим добавления в форме|`Boolean`|`false`|`false`|
|isAddingInline|Режим добавления в строке|`Boolean`|`false`|`true`|
|isEditable|Режим редактирования|`Boolean`|`false`|`true`|
|isEditableForm|Режим редактирования в форме|`Boolean`|`false`|`false`|
|isEditableInline|Режим редактирования в строке|`Boolean`|`false`|`true`|
|isFooter|Отображение подвала|`Boolean`|`false`|`false`|
|isExpansion|Режим раскрытия строк|`Boolean`|`false`|`false`|
|isMultiline|Многострочный режим|`Boolean`|`false`|`false`|
|isHierarchy|Иерарический режим|`Boolean`|`false`|`true`|

#### События
|Event Name|Description|Parameters|
|---|---|---|
|blur:table|Потеря фокуса таблицей|-|
|editing:element|Редактирование элемента|`options: {}`|
|focused:element|Сфокусирован элемент таблицы|`element: {}`|
|mounted:table|Таблица смонтирована на страницу|`optionsTable: {}`|
|selected:element|Выбор элемента (двойной клик)|`element: {}`|
