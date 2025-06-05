<h1 align="center"> Analisis AluraStore </h1>

<h2> Descripción del Proyecto </h2>
En este proyecto se hizo un analisis sobre un hipotetico caso donde el Sr.Juan tiene cuatro tiendas y necesita cerrar definitivamente una. Se analizaron vistas generales y espeficicas para llegar a la mejor conclusion y poder dar el mejor analisis posible.

<h2> Herramientas utilizadas </h2>
Se utilizo Python con librerias pandas y matplotlib en colab

<h2> Vista previa del proyecto  </h2>

``````
```
ranking_promedios = [
    calificacion_promedio_tienda,
    calificacion_promedio_tienda2,
    calificacion_promedio_tienda3,
    calificacion_promedio_tienda4
]
ranking_tiendas = ['Tienda 1', 'Tienda 2', 'Tienda 3', 'Tienda 4']

plt.figure(figsize=(8, 5))
plt.plot(ranking_tiendas, ranking_promedios, marker='o', linestyle='-', color='green')
plt.title("Promedio de Calificación por Tienda")
plt.xlabel("\nTienda")
plt.ylabel("\nPromedio de Calificación\n")
plt.ylim(min(ranking_promedios) - 0.1, max(ranking_promedios) + 0.1)
plt.grid(True)
plt.show()
```
``````

![imagengrafico](https://github.com/user-attachments/assets/3ff671b0-a78a-44f8-bc16-1a36b01cbb74)


