### ¿Qué se pretende implementar como una actividad?
* Vista de categorías (CategoriesActivity)
* Creación de categorías (CreateCategoriesActivity)
* Creación de gasto (GastoActivity)
* Creación de gasto grupal (GastoGrupoActivity)
* Visualización de estadísticas (StatsActivity)

### ¿Qué se va a implementar como un servicio?
* Adición de gastos
* Reconocimiento de facturas

### ¿Qué se va a implementar con fragments?
* Vista personal
* Vista grupal
* Gráfica de gastos
* Gráfica de estadísticas
* Gastos en cada pantalla

### ¿Quién lanza a quién y quién hace uso de los fragments o los servicios?
La actividad principal (MainActivity) lanza el fragment de vista Personal, en el cual se puede ver los distintos gastos y la gráfica, este fragment lanza la actividad que permite ver las estadísticas (StatsActivity) y la actividad que visualiza las categorías (CategoriesActivity) desde la que se lanza la actividad para crear categorías (CreateCategoriesActivity), además, desde el fragment de vista Personal, se puede crear un nuevo gasto (GastoActivity), que usará el servicio de Adición de gastos y Reconocimiento de facturas, de la misma forma, desde el fragment de vista Grupal se puede acceder a distintos grupos en los que se carga el fragment de gastos y el de la gráfica, de la misma forma que en la vista Personal y se lanza la actividad de creación de un nuevo gasto grupal (GastoGrupoActivity).

### Mockups de pantallas grandes o tablets
![image](https://github.com/alvaroddiaz/APM/assets/72129484/0af9465c-e601-466a-807b-01fa242aa97a)
![image](https://github.com/alvaroddiaz/APM/assets/72129484/5bcfc527-f9ef-49ac-a654-938b294b8180)
![image](https://github.com/alvaroddiaz/APM/assets/72129484/0e8fdecd-2324-4a1e-ae53-928d613c64cf)

