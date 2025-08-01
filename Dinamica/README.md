# Dinámica

## Rotación
**PD:** *Los ángulos ponlos en el mismo sistema que en el que esté la calculadora, si está en grados pos grados, si está en radianes pos radianes*

### Rx_a( ángulo )
**Matriz de Rotación ACTIVA** en x
#### Ejemplo:
___
### Ry_a( ángulo )
**Matriz de Rotación ACTIVA** en y
#### Ejemplo:
___
### Rz_a( ángulo )
**Matriz de Rotación ACTIVA** en z
#### Ejemplo:
___
### REuler_p( θ, ɸ, ψ) 
**Matriz de Rotación pasiva de Euler** (concretamente una rotación z, x', z" con ángulos θ, ɸ, ψ )
#### Variables

 - θ = ángulo
 - ɸ = ángulo
 - ψ = ángulo

#### Ejemplo:
___
### Ang_Euler_a( Rotación )
Saca los ángulos de Euler (activos, suppossedly) de una matriz de rotación.

#### Variable
- Rotación = Matriz
#### Ejemplo:
___
### RExp( VelAngular_t )
Calcula la matriz de rotación de Rodrigues a través de R=exp(  matriz velocidad angular * t)

#### Variable
- VelAngular_t = Matriz velocidad angular multiplicada por el tiempo, osea  [[velocidad angular]]*t 

#### Ejemplo:
___
### Vec2Mat( vector )
Convierte los vectores velocidad angular y aceleración angular en sus respectivas matrices

#### Variable
- vector = vector 3x3 en fila [x,y,z]

#### Ejemplo:

___
