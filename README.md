# Employee Management System

## Описание проекта

Проект представляет собой систему управления сотрудниками, реализованную на языке программирования Java. Основной компонент системы - класс `Employee`, который описывает информацию о сотруднике.

## Класс Employee

### Описание

Класс `Employee` представляет собой модель данных для хранения информации о сотруднике компании. Каждый объект этого класса содержит следующие атрибуты:

- `id` (int): уникальный идентификатор сотрудника.
- `fullName` (String): полное имя сотрудника.
- `position` (String): должность сотрудника.
- `department` (String): отдел, в котором работает сотрудник.
- `salary` (double): заработная плата сотрудника.

### Методы

1. **Конструкторы:**
    - `public Employee(int id, String fullName, String position, String department, double salary)`: создает новый объект `Employee` с заданными параметрами.
    - `public Employee()`: конструктор по умолчанию.

2. **Геттеры и сеттеры:**
    - `public int getId()`: возвращает идентификатор сотрудника.
    - `public void setId(int id)`: устанавливает идентификатор сотрудника.
    - `public String getFullName()`: возвращает полное имя сотрудника.
    - `public void setFullName(String fullName)`: устанавливает полное имя сотрудника.
    - `public String getPosition()`: возвращает должность сотрудника.
    - `public void setPosition(String position)`: устанавливает должность сотрудника.
    - `public String getDepartment()`: возвращает отдел, в котором работает сотрудник.
    - `public void setDepartment(String department)`: устанавливает отдел, в котором работает сотрудник.
    - `public double getSalary()`: возвращает заработную плату сотрудника.
    - `public void setSalary(double salary)`: устанавливает заработную плату сотрудника.

3. **Прочие методы:**
    - `public String toString()`: возвращает строковое представление объекта `Employee`.

## Пример использования

```java
public class Main {
    public static void main(String[] args) {
        // Создание объекта Employee
        Employee employee = new Employee(1, "Иванов Иван", "Разработчик", "IT", 50000.0);

        // Вывод информации о сотруднике
        System.out.println("Информация о сотруднике:");
        System.out.println(employee);
    }
}
```

## Лицензия

Этот проект распространяется под лицензией [MIT](LICENSE). Подробности см. в файле `LICENSE`.