# PedidosApp

Aplicación de escritorio para la gestión y simulación de entregas de pedidos, desarrollada en C# con Windows Forms.

## 🎯 Propósito

Simular diferentes estrategias de entrega de productos según sus características (peso, tipo, urgencia) y registrar los pedidos realizados.

## 🛠️ Funcionalidades implementadas

- Estrategias de entrega: Dron, Moto, Camión y Bicicleta (ecológica).
- Registro de pedidos con sus datos clave: producto, tipo, peso, distancia, urgencia.
- Persistencia de pedidos mediante lista local.
- Formulario para ver historial de pedidos con **filtros por tipo de entrega**.
- Cálculo automático del costo de entrega según la estrategia seleccionada.

## 🌱 Mi estrategia ecológica

Se agregó la entrega en bicicleta bajo la siguiente condición:

> Si el pedido es de tipo **accesorio**, pesa menos de **2 kg** y **no es urgente**, se utiliza bicicleta como método de entrega con un costo de `3 * km`.

## 📋 Requisitos

- Visual Studio 2019 o superior
- .NET Framework 4.7.2 o compatible

## ▶️ Cómo ejecutar

1. Abre la solución `PedidosApp.sln` en Visual Studio.
2. Establece el proyecto `PedidosApp` como proyecto de inicio.
3. Ejecuta con `F5` o desde el menú de depuración.

## 📸 Evidencias requeridas

Incluye capturas de pantalla de:

- Formulario principal con un pedido generado.
- Formulario de historial de pedidos con el filtro aplicado.

## 📁 Estructura del proyecto

