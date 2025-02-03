# Завдання 1. Створення та запуск першої програми (сорочки)


1. Cтворіть в теці `src` новий файл `Shirt.java`, в якому наберіть наступний код:
```Java
public class Shirt {
  public int shirtID = 0; // стандартне значення номера моделі сорочки
  public String description = "-description required-"; // стандартний опис сорочки
  // коди кольорів: R=червоний, B=синій, G=зелений, U=невідомо
  public char colorCode = 'U';
  public double price = 0.0; // стандартна вартість сорочки
  public int quantityInStock = 0; // стандартна кількість на складі
  
  // цей метод просто виводить всю інформацію про сорочку на екран
  public void displayShirtInformation() {
    System.out.println("Shirt ID: " + shirtID);
    System.out.println("Shirt description:" + description);
    System.out.println("Color Code: " + colorCode);
    System.out.println("Shirt price: $" + price);
    System.out.println("Quantity in stock: " + quantityInStock);
  } // кінець методу displayShirtInformation
} // кінець опису класу
```

2. Збережіть файл, у разі необхідності (аби "навести красу" з відступами) скористайтесь швидким форматуванням - `ALT`+`SHIFT`+`F`
3. Відкрийте файл `ShirtTest.java` з цього репозиторію
4. Запустіть його (`F6` у `NetBeans` для запуску головного виконуваного файлу, `SHIFT`+`F6` - для запуску поточного файлу)
5. Зробіть та збережіть (тека `Solution`) у файл `task1.1.png`
![Task 1.1](https://github.com/ppc-ntu-khpi/java-first-Glerik23/tree/main/Solution/task1.1.png)

6. Замініть у файлі `Shirt.java` номер сорочки, її опис та вартість довільними значеннями
7. Запустіть файл повторно
8. Зробіть та збережіть у файл `task1.2.png`
![Task 1.2](https://github.com/ppc-ntu-khpi/java-first-Glerik23/tree/main/Solution/task1.2.png)

9. На "п'ять" - те, що на "чотири", плюс, змінити код завдань таким чином, щоб:
колір сорочки зберігався та виводився у вигляді рядка (red, blue, green, unset)
![Task 1.3](https://github.com/ppc-ntu-khpi/java-first-Glerik23/tree/main/Solution/task1.3.png)