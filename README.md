## Отчёт о тестировании приложения "Precision"
   Precision - приложение, которое расчитывает дополнительный бонус новым клиентам.
   
   27.08.2020 было проведено функциональное тестирование бонусной программы.
   
   На тестирование затрачено 0,5 ч.
   
   #### В результате тестирования выявлены следующие дефекты:
   
   При сложении скидки 0,3 и скидки 0,6 результат 0.8999999999999999
   
   ![image](https://user-images.githubusercontent.com/67522974/91500043-562cc080-e8cb-11ea-86fe-1ad0ba52f458.png)
   
   ### В качестве тестовых данных использовалось:
   
   ```Java
   public class Main {
     public static void main(String[] args) {
       double regularBonus = 0.3;
       double specialBonus = 0.6;
       double totalBonus = regularBonus + specialBonus;
       System.out.println(totalBonus);
     }
   }
```
   
   ### Результаты
   
  [Баг Репорт](https://github.com/FadeevaDari/JAVA_HW2.2/issues)
   
   
   Тестирование производилось в следующем окружении:
   Windows 10 Professional 64х Версия Java "11.0.8" Google Chrome Версия 84.0.4147.135