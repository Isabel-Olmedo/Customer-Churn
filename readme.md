# BCG Data Science & Analytics Virtual Experience Program

![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png)

### 1. Contexto

PowerCo es una importante empresa de servicios públicos de gas y electricidad que suministra a clientes corporativos, pymes (pequeñas y medianas empresas) y residenciales. La liberalización energética del mercado de la energía en Europa ha provocado una importante rotación de clientes, especialmente en el segmento de las pymes. Se han asociado con BCG para ayudar a diagnosticar el origen de la rotación de clientes de pymes.

---

### 2. Hipótesis

¿La rotación está impulsada por la sensibilidad al precio de los clientes?

---

### 3. Usando un modelo predictivo
PowerCo necesita diagnosticar el origen de la perdida de clientes, para saber quienes son los clientes con mas o menos probabilidades de abandonar la empresa.

* Para esos clientes que estan en riesgo de abandonar, PowerCo quiere ofrecerles un 20% de descuento para incentivarlos a quedarse.
* PowerCo planea usar el modelo predictivo el primer dia de cada mes para indicar a que clientes se les deberia ofrecer el descuento.

---

### 4. Resultados

1.  9.7% de 14606 clientes PYMES han abandonado PoweCo.
2. La sensibilidad al precio no es el principal factor en la perdida de clientes, es un contribuyente débil.
3. Customer churn es afectado principalmente por otras variables, las principales son:
	- Consumo de electricidad en los pasados 12 meses
	- Margen en la suscripción de energía
	- Previsión de la factura de alquiler de contadores para los próximos 12 meses.
	- Margen neto total.

---

### 5. ¿Qué perfil tienen los clientes con mayor potencial de abandonar la empresa?

Con este análisis, el perfil del cliente que podría abandonar la empresa y a quien le podría  ofrecer un descuento seria:

- Clientes con un margen total mayor a 1250
- Con un margen bruto en la suscripción de energía >=90
- Suscrito a una potencia máxima mayor o igual a 75
- Menos de 5 años de antigüedad
- Con menos de 5 productos
- Tener un consumo de energía en los últimos 12 meses menor o igual a 1,500,000
- Haber consumido el mes pasado menos de 300,000 de energía.

---
### 6. Recomendaciones

- Seleccionar a clientes con una alta probabilidad de abandonar la empresa para ofrecerles el descuento.
- Analizar comentarios del cliente: un registro de seguimiento de cualquier queja, llamada o comentario proporcionado por el cliente a PowerCo podría revelar si es probable que un cliente abandone.
- Crear un sentido de pertenencia entre los clientes.



