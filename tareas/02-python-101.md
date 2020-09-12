
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

#GASTO PER CAPITA

def per_capita(cantidad, poblacion):
  return (cantidad/poblacion)

cantidad2019 = 12894090259
cantidad2020 = 13517480531
poblacion = 119938473
capita2019 = per_capita(cantidad2019, poblacion)
capita2020 = per_capita(cantidad2020, poblacion)
print(f'El gasto per capita 2019 es: ${round(capita2019,2)}' )
print(f'El gasto per capita 2020 es: ${round(capita2020,2)}' )

#indice
def indice(anterior, actual):
  return (actual/anterior)

cantidad2019 = 12894090259
cantidad2020 = 13517480531
indicador = indice(cantidad2019, cantidad2020)
print(f'Indice del gasto 2020 resapecto al 2019: {round(indicador,2)}')

#aumento un 5%
```
