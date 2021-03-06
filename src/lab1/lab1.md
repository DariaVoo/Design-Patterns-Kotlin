#  Порождающие паттерны.
Порождающие паттерны проектирования абстрагируют процесс инстанцирования объектов.
Они позволяют сделать код независимым от способа создания, композиции и представления используемых в его работе объектов.

## Паттерн Одиночка (Singleton).
Гарантирует, что у класса есть только один экземпляр, и предоставляет к нему глобальную точку доступа.

_Задание:_

Реализовать паттерн порождающего проектирования Одиночка (singleton).

[Решение](Singleton.kt)

## Паттерн Абстрактная фабрика (Abstract Factory).
Предоставляет интерфейс для создания семейств взаимосвязанных или взаимозависимых объектов, не специфицируя их конкретных классов.

_Задание:_

Обеспечить контроль загрузки и готовности к отправлению автобусов и такси.
* Водитель такси и автобуса имеют права разной категории.
* Без водителя машина не поедет.
* Два водителя в одну машину сесть не могут.
* Без пассажиров машины не поедут.
* Есть лимит загрузки машин. Для автобуса 30 чел. Для такси 4 чел.
Рекомендуется для водителя применить паттерн синглтон.

[Решение](AbstractFactory.kt)

## Тесты
* [Задание 1](SingletonTest.kt)
* [Задание 2](AbstractFactoryTest.kt)
