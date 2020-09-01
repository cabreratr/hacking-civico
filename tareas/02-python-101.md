
```python
#se define la función densidad_poblacion
def densidad_poblacional(poblacion, area_ciudad):
  return (poblacion / area_ciudad)

#Ciudad Villaflores: 98,618 superficie: 1,232 
#se calcula la densidad poblacional de la ciudad
densidad_cd = densidad_poblacional(98618, 1232)

#Estado Chiapas poblacion: 5,228,711, superficie: 73,211
#se calcula la densidad poblacional del estado de Chiapas
densidad_edo = densidad_poblacional(5228711, 73211)

#País poblacion: 119,938,473 superficie: 1,964,375
#se calcula la densidad poblacional de México
densidad_pais = densidad_poblacional(119938473, 1964375)

#Se muestran los resultados
print(f'Densidad poblaiconal del la ciudad: {round(densidad_cd, 2)} hab/km²')
print(f'Densidad poblaiconal del estado: {round(densidad_edo, 2)} hab/km²')
print(f'Densidad poblaiconal del país: {round(densidad_pais, 2)} hab/km²')
```
