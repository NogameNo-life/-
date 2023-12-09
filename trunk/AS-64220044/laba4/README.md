# Лабораторная работа №4 #

## Тема ##

### Обследование объекта автоматизации: построение информационной модели ###

## Цель ##

### Изучить и построить процессную модель объекта автоматизации ###

## Вариант 1 - Аптека ##

```mermaid
flowchart TB
node1[Формирование заказа и согласование с поставщиком]
node2[Подача заявки на доставку]
node3[Заказ]
node4[Менеджер]
node5[Поставщик]
node6[Товары]
node7[Поступление товара]
node8[Приемка товара]
node9[Электроннная ТТН]
node10[Товар]
node11[ТТН поставщика]
node12[Заявка на отправку]
node13[Менеджер]
node14[Товары]
node15[Товар получен]
node16[Определение товара на скалад]
node17[Приходный ордер]
node18[Менеджер]
node19[Эл.ТТН]
node20[Скалд]
node21[Товар]
node22[Кладовщик]
node23[Приходный ордер сотсавлен]
node24[Формирование отчета]
node25[Оборото - сальдовая ведомость]
node26[Менеджер]
node27[Отчет оформлен]
node1-->node2
node2-->node3
node4-->node2
node5-->node2
node6-->node2
node2-->node7
node7-->node8
node8-->node9
node8-->node10
node11-->node8
node12-->node8
node13-->node8
node14-->node8
node8-->node15
node15-->node16
node16-->node17
node18-->node16
node19-->node16
node20-->node16
node21-->node16
node22-->node16
node16-->node23
node23-->node24
node24-->node25
node26-->node24
node24-->node27
```