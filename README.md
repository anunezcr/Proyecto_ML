# Proyecto_ML
Proyecto del Curso Machine Learning - FUNDATEC

Cada línea contiene información de un día (una fecha de un año "cualquiera"), para una sucursal

Para pre-procesado incluye:
  algunos NaNs
  varios valores categóricos
 
Incluye información estacional de la fecha, lo que se cree influye en la cantidad de clientes del día
  si es quincena
  si es un día feriado
  dia de la semana
  otros
 
Otros datos:
  cantidad de cajas registradoras utilizadas en el día
  cantidad de horas de operación para ese día para esa sucursal
  
Información de clientes atendidos
  clientes totales para ese día y esa sucursal
  cantidad de clientes niños (relevante para el tipo de negocio)
  
Planteamiento hipotético del problema:
  1. Regresión:
  Pronosticar la  cantidad de clientes totales y clientes niños que serán atendidos en fechas futuras
  
  *******************************
  
  2. Clasificación
  2.1 Interés para el gerente de Operaciones:
  Establecer 3 clusters según cantidad de clientes totales para fechas futuras
      Rojo:   volumen alto, requiere personal adicional, supervisión/consultoría presencial, y aumentar previsión de materia prima o insumos
      Naranja:volumen medio, requiere reforzar procedimientos y controles operativos
      Verde:  volumne bajo, no requiere atención especial
      
  2.2 Interés para departamento que atiende la experiencia de niños:
  Clusters según cantidad de clientes niños
  Rojo, Naranja, Verde para tomar decisiones específicas de atención a este tipo de cliente
      
  2.3 Se sospecha que la relación entre clientes totales y clientes niños es independiente, y varía de una sucursal a otra
  Un rojo operativo no necesariamente es rojo niños
  ¿El modelo de Clasificación puede confirmar dicha sospecha?
