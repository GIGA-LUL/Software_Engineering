![image](https://github.com/user-attachments/assets/1082ad15-9fdd-4926-91dd-25f6385c60a0)# Тема 2. Базовые операции языка Python.
Отчёт по теме #2 выполнил:

- Андреев Сергей Андреевич
- АИС-22-1

| Задание | Лаб_раб | Сам_Раб |
| :------------ | :------------ | :------------ |
| Задание 1 | + | + |
| Задание 2 | + | + |
| Задание 3 | + | + |
| Задание 4 | + | + |
| Задание 5 | + | + |
| Задание 6 | + | + |
| Задание 7 | + | + |
| Задание 8 | + | + |
| Задание 9 | + | + |
| Задание 10 | + | + |
| Задание 11 | + | + |
| Задание 12 | + | + |
| Задание 13 | + | + |
| Задание 14 | + | + |
| Задание 15 | + | + |

знак "+" - задание выполнено; знак "-" - задание не выполнено

Работу проверил:

- к.э.н., доцент Панов М.А.

# Лабораторная работа №2
## 1. Выведите в консоль три строки. Первая – любое число. Вторая – любое число в виде строки. Третья – любое число с плавающей точкой.

```python
print(88005553535)
print('88005553535')
print(8800.5553535)
```

**Результат:**
![image](https://github.com/user-attachments/assets/62f59322-47f1-4068-8aba-160c03c58551)

## 2. Выведите в консоль три строки. Первая – результат сложения или вычитания минимум двух переменных типа int. Вторая – результат сложения или вычитания минимум двух переменных типа float. Третья – результат сложения или вычитания минимум двух переменных типа int и float.

```python
n = m = 5
a = b = 13.5
print(n+m)
print(a-b)
print(n+a-2*m)
```

**Результат:**
![image](https://github.com/user-attachments/assets/9b8cc52b-e62f-42bd-8838-9e133bbdce73)

## 3. Выведите в консоль три строки. Первая – обычная строка. Вторая – F строка с использованием заранее объявленной переменной. Третья – сложите две или более строк в одну.

```python
a_str = "qwerty"
print(a_str)
print(f"Вывожу {a_str}")
print(a_str + a_str)
```

**Результат:**
![image](https://github.com/user-attachments/assets/34bbb8cf-0a23-4dce-8d36-52a2f24562af)

## 4. Выведите в консоль три строки. Первая – трансформация любого типа переменной в bool. Вторая – трансформация любого типа переменной в float или int. Третья – трансформация любого типа переменной в str.

```python
a_int = 5
print(bool(a_int))
print(float(a_int))
print(str(a_int))
```

**Результат:**
![image](https://github.com/user-attachments/assets/dccebaa1-3929-4873-b173-e9a9ed299098)

## 5. Присвойте трем переменным различные значения, воспользовавшись функцией input()

```python
a = str(input('Меня зовут '))
b = int(input('Я умею считать до '))
c = float(input('Число pi: '))/7
print(a, b, c)
```

**Результат:**
![image](https://github.com/user-attachments/assets/b31c202c-b754-497f-adb4-8f1e63a6f880)

## 6. Создайте две любые числовые переменные и выполните над ними несколько математических операций: возведение в степень, обычное деление, целочисленное деление, нахождение остатка от деления. При желании вы можете проверить как работают эти вычисления с разными типами данных, например, сначала создать две переменные int, затем создать две переменные float и наконец создать переменные типа int и float и провести над ними операции, прописанные выше.

```python
a = 123
b = float(789)
print((a / 12) ** (b/50))
print(b / a)
print((a*5) // b)
print((b*3) % a)
```

**Результат:**
![image](https://github.com/user-attachments/assets/2a26e0d9-cebc-4c86-b325-d32a042975c2)

## 7. Создайте любую строковую переменную и произведите над ней математическое действие умножение на любое число.

```python
a = "qwe"
print(a * 10)
```

**Результат:**
![image](https://github.com/user-attachments/assets/736f5517-5754-41d8-ad9d-66e9f4e79441)

## 8. Посчитайте сколько раз символ ‘o’ встречается в строке ‘Hello World’.

```python
print("Hello World".count('o'))
```

**Результат:**
![image](https://github.com/user-attachments/assets/01e9c43e-3746-45d3-9920-589c5d9ea458)

## 9. Напишите предложение ‘Hello World’ в две строки. Написанная программа должна занимать одну строку в редакторе кода.

```python
print("Hello World"+'\n'+"Hello World")
```

**Результат:**

## 10. Из предложения ‘Hello World’ выведите в консоль только 2 символ, а затем выведите слово ‘Hello’

```python
print("Hello" + '\n' + "World")
```

**Результат:**
![image](https://github.com/user-attachments/assets/39bb60c7-f44e-49cb-82e7-eace368fe3a3)

# Самостоятельная работа №2
## 1. Выведите в консоль булевую переменную False, не используя слово False в строке или изначально присвоенную булевую переменную. Программа должна занимать не более двух строк редактора кода.

```python
print(0 == 1)
```

**Результат:**
![image](https://github.com/user-attachments/assets/d0bb4607-a20a-48b4-b98e-850f7b4b60ca)

## 2. Присвоить значения трем переменным и вывести их в консоль, используя только две строки редактора кода

```python
(a, b, c) = (1, 2, 3)
print(a, b, c)
```

**Результат:**
![image](https://github.com/user-attachments/assets/b09a8271-adf0-46d2-ade7-cf90a1016489)

## 3. Реализуйте ввод данных в программу, через консоль, в виде только целых чисел (тип данных int). То есть при вводе буквенных символов в консоль, программа не должна работать. Программа должна занимать не более двух строк редактора кода.

```python
a = int(input())
print(a)
```

**Результат:**
![image](https://github.com/user-attachments/assets/c44ee1ab-9c25-4731-9767-73a86c59f10e)

## 4. Создайте только одну строковую переменную. Длина строки должна не превышать 5 символов. На выходе мы должны получить строку длиной не менее 16 символов. Программа должна занимать не более двух строк редактора кода.

```python
a = "abob"
print(a * 10)
```

**Результат:**
![image](https://github.com/user-attachments/assets/9e4d6f69-c8d2-490f-96d6-b07ca1bf1c61)

## 5. Создайте три переменные: день (тип данных - числовой), месяц (тип данных - строка), год (тип данных - числовой) и выведите в консоль текущую дату в формате: “Сегодня день месяц год. Всего хорошего!” используя F строку и оператор end внутри print(), в котором вы должны написать фразу “Всего хорошего!”. Программа должна занимать не более двух строк редактора кода.

```python
(dd, mm, yyyy) = (int(18), "09", int(2024))
print(f"Сегодня {dd} {mm} {yyyy}.", end=" Всего хорошего!")
```

**Результат:**
![image](https://github.com/user-attachments/assets/4d85fe89-ca5d-4075-971f-3343659a1a58)

## 6. В предложении ‘Hello World’ вставьте ‘my’ между двумя словами. Выведите полученное предложение в консоль в одну строку. Программа должна занимать не более двух строк редактора кода.

```python
print(" my ".join("Hello World".split()))
```

**Результат:**
![image](https://github.com/user-attachments/assets/21598998-09ea-4813-8dff-bbdc9b2064fc)

## 7. Узнайте длину предложения ‘Hello World’, результат выведите в консоль. Программа должна занимать не более двух строк редактора кода.

```python
print(len("Hello World"))
```

**Результат:**
![image](https://github.com/user-attachments/assets/0deed74f-37c7-4e3e-ac0b-e466b23f5e57)

## 8. Переведите предложение ‘HELLO WORLD’ в нижний регистр. Программа должна занимать не более двух строк редактора кода.

```python
print(len("Hello World"))
```

**Результат:**
![image](https://github.com/user-attachments/assets/f960b678-d36e-4adf-8170-029556139760)

## 9. Самостоятельно придумайте задачу по проходимой теме и решите ее. Задача должна быть связанна со взаимодействием с числовыми значениями.
### Задача: Выведите в консоль результат деления целых чисел посредством операций целочисленного деления и получения остатка от деления, занимая при этом не более одной строки кода.

```python
print(str(10000//23) + "." + str(10000%23))
```

**Результат:**
![image](https://github.com/user-attachments/assets/8a337ea9-9697-4600-92d1-63df7fa4aebe)

## 10. Самостоятельно придумайте задачу по проходимой теме и решите ее. Задача должна быть связанна со взаимодействием со строковыми значениями.
### Задача: Объявите переменную типа string со значением на входе в виде одной цифры и, используя её, выведите две строки в виде чисел с длиной более 5 символов двумя разными способами. Программа должна занимать не более двух строк редактора кода.

```python
a = "5"
print(f"Первая строка с первым числом {a*10} и вторым числом {5*a} \n" + "Вторая строка с первым числом " + a[0]*5 + " и вторым числом " + str(int(a[0])*100000))
```

**Результат:**
![image](https://github.com/user-attachments/assets/da8506cd-a935-4d19-8cff-9186652aea6b)

