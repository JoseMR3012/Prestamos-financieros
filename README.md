# Prestamos-financieros
# dsrp_prestamos_financieros_bda_6

##Caso: Gestión de Préstamos Financieros
Una entidad financiera necesita un sistema para administrar los préstamos otorgados a sus clientes. Este sistema debe permitir registrar y consultar información sobre los clientes, los préstamos otorgados, las cuotas generadas y los pagos realizados.

#Requerimientos:

##Clientes:

Se debe almacenar información básica de los clientes, como su tipo (persona natural o jurídica), nombre completo o razón social, número de identificación, dirección, teléfono y correo electrónico.

##Préstamos:

Cada préstamo debe estar asociado a un cliente.
Se debe registrar el monto otorgado, la tasa de interés, el plazo (en meses), la fecha de inicio y la fecha de vencimiento.
Un préstamo puede ser de diferentes tipos, como personal, hipotecario o vehicular.

##Cuotas:

Cada préstamo genera un cronograma de cuotas con su número de cuota, monto, fecha de vencimiento y estado (pendiente, pagada, vencida).
El cálculo de las cuotas debe considerar el monto del préstamo, la tasa de interés y el plazo.

##Pagos:

Los clientes pueden realizar pagos parciales o totales de una o más cuotas.
Se debe registrar la fecha del pago, el monto abonado y la cuota o cuotas asociadas.

##Sucursales (opcional):

Cada préstamo debe estar vinculado a la sucursal donde fue otorgado.
Cada sucursal tiene un código único, dirección y gerente asignado.

## Modelo Entidad Relación
![MODELO CONCEPTUAL BDA 5](https://github.com/user-attachments/assets/f4d51269-3d2b-49ee-8a93-589c62586ce3)

## Modelo Lógico
![db_prestamos_1](https://github.com/user-attachments/assets/83cbf55b-68e0-4f77-8a58-3403127ce334)
## Modelo Físico
![image](https://github.com/user-attachments/assets/ebbb3a55-9a90-4244-a785-d0b6d767c3a1)


