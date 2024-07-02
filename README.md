# Здания и квартиры

Этот репозиторий содержит простое консольное приложение и DLL-библиотеку для управления зданиями и квартирами.

## Автор

Корчагина

## BuildingLibrary

Проект BuildingLibrary содержит два класса: Building и Apartment. Класс Building включает Address, Description, Apartments (список квартир) и метод ShowAll(). Класс Apartment включает Number, Owner и метод Show(). Класс Apartment также реализует интерфейс IComparable.

## BuildingConsoleApp

Проект BuildingConsoleApp является простым консольным приложением, которое использует DLL-библиотеку BuildingLibrary. Метод Main() создает объект Building, добавляет в него 3-5 объектов Apartment и отображает информацию о всех квартирах, отсортированных по их номерам, с помощью метода ShowAll().
