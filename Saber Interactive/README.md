# Тест для соискателей вакансии программист

Уважаемый соискатель, перед Вами тест на вакансию программист в компании Saber Interactive. Индустрия видеоигр, в которой работает компания Saber, предъявляет высокие требования к качеству, эффективности и удобству восприятия программного кода. Поэтому мы предлагаем выполнить Вам несложное задание, чтобы Вы могли продемонстрировать Вашу способность писать такой код.

Фамилия, имя, отчество выполнившего тест:
Дата выполнения:
Примерное количество времени, затраченного на выполнение теста: 

## Задача
Реализуйте функции сериализации и десериализации двусвязного списка, заданного следующим образом:

```
 class ListNode
    {
 public ListNode Previous;
        public ListNode Next;
        public ListNode Random; // произвольный элемент внутри списка
        public string Data;
    }


    class ListRandom
    {
        public ListNode Head;
        public ListNode Tail;
        public int Count;

        public void Serialize(Stream s)
        {
        }

        public void Deserialize(Stream s)
        {
        }
    }
```

Примечание: сериализация подразумевает сохранение и восстановление полной структуры списка, включая взаимное соотношение его элементов между собой.
Напишите программу, демонстрирующую работу реализованных функций сериализации и десериализации на небольшом наборе тестовых данных (списке из нескольких элементов). Тест нужно выполнить без использования библиотек/стандартных средств сериализации. Сигнатуры методов serialize/deserialize менять нельзя, также не изменяя содержимое класса ListNode. 