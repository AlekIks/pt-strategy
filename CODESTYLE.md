# Правила написания кода:
* Минимизировать количество нижних подчеркиваний.
* Названия методов, полей и переменных нужно писать с маленькой буквы, используя camelCase,
 классов - с большой, также используя CamelCase.
* Отступ - 4 пробела.
* Вокруг круглых скобок при вызове функций и в синтаксических
 конструкциях пробелов нет.
* Перед запятой пробела нет, после нее есть.
* Аналогично с точкой с запятой.
* Слева и справа от точки пробела нет.
* Открывающая фигурная скобка должна быть на той же строке.
* Если одновременно объявляем несколько переменных одного типа, то каждую на новой строке.
* При объявлении массива квадратные скобки как в примере.
* По возможности инициализировать все переменные.


## Пример:

```java
public class Main {
    public static void main(String [] args) {
        int a = 10;
        int b = 20;
        int [] c = {1, 2, 3};
        
        T myVariable = new T("Title", 1, 2);
        
        int k = a + b;
        
        int l = Main.myFunction();
    }
    
    private static int myFunction() {
        return 10;
    }
}
```