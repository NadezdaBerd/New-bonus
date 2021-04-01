# Отчёт о тестировании приложения "Бонус для новых клиентов"


02.04.2021 было проведено функциональное тестирование работы кода приложения "Бонус для новых клиентов".

На тестирование затрачено: 5 мин.

В результате тестирования выявлены следующие дефекты:
[Некорректно выводится итоговый бонус](https://github.com/NadezdaBerd/New-bonus/issues/1#issue-848809158)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Код программы приложения "Бонус для новых клиентов", созданный в приложении IntelliJ IDEA:
```
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
```


В качестве тестовых данных использовались данные из кода:
* regularBonus = 0.3
* specialBonus = 0.6
* totalBonus = regularBonus + specialBonus

Тестирование производилось в следующем окружении:
* Windows 10, х64
* Java 11.0.10
* IntelliJ IDEA Community Edition 2020.3.3
