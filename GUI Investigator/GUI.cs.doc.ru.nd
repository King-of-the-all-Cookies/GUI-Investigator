#Документация для файла GUI.cs

Этот файл определяет класс GUI, который отвечает за взаимодействие с графическим интерфейсом в проекте GUI Investigator. Он включает в себя функциональность для чтения и записи данных в формате байтов и XML, а также для работы с различными анимациями, панелями и событиями.

##Класс GUI

Класс GUI представляет собой основную структуру для хранения информации о графическом интерфейсе. Он содержит различные поля, атрибуты и методы для работы с данными.

##Поля класса





int filenameHash - Хеш имени файла.



int flag0, flag1, otherflags - Флаги для различных настроек.



int somecount0, somecount1, somecount2, somecount3, othercount - Счетчики для различных элементов.



List anims - Список анимаций.



List panes - Список панелей.



List events - Список событий.



Unknown unknown - Содержит неизвестные элементы.

##Методы класса

FromByteArray

public static GUI FromByteArray(byte[] bytes) - Этот метод позволяет создавать экземпляр класса GUI из массива байтов. Он читает различные заголовки и данные, а затем заполняет поля класса соответствующими значениями.

##Пример использования:
```cs
byte[] rawData = ...; // Полученные данные в виде массива байтов
GUI guiInstance = GUI.FromByteArray(rawData);
```
##ToByteArray

public byte[] ToByteArray() - Данный метод позволяет конвертировать экземпляр класса GUI обратно в массив байтов. Это полезно для сохранения состояния интерфейса.

##Пример использования:
```cs
GUI guiInstance = new GUI();
byte[] rawData = guiInstance.ToByteArray();
```
##FromXmlString

public static GUI FromXmlString(string xml) - Метод для создания экземпляра GUI из XML-строки. Это позволяет легко импортировать данные из формата XML.

##Пример использования:
```cs
string xmlData = ...; // Полученные данные в формате XML
GUI guiInstance = GUI.FromXmlString(xmlData);
```
##ToXmlString

public string ToXmlString() - Метод для конвертации экземпляра класса GUI в XML-строку. Это удобно для экспорта данных в формате XML.

##Пример использования:
```cs
GUI guiInstance = new GUI();
string xmlData = guiInstance.ToXmlString();
```
