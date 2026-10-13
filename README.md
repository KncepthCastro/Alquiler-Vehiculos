<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2D1B3D,100:4A2C5E&height=180&section=header&text=Ejercicio%20%C2%B7%20Alquiler%20de%20Veh%C3%ADculos%20%F0%9F%9A%97&fontSize=38&fontColor=FAF6EE&animation=fadeIn&fontAlignY=38" />

### 💜 Java + NetBeans 🌸

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=C8A2E0&center=true&vCenter=true&width=600&lines=C%C3%A1lculo+del+total+a+pagar;Aplicaci%C3%B3n+de+escritorio;Java+%7C+NetBeans;L%C3%B3gica+por+tramos+y+descuentos" alt="Typing SVG" />

</div>

Aplicación de escritorio desarrollada en **Java** con **NetBeans** que calcula el **total a pagar** por el alquiler de un vehículo, a partir de la cantidad de días, el precio por día y el tipo de cliente.

---

### 🎯 Objetivo

Solicitar al usuario los datos necesarios y aplicar de forma secuencial los cargos y descuentos correspondientes para obtener el monto final a pagar.

**Datos de entrada:**

- 📅 Cantidad de días de alquiler
- 💵 Precio de alquiler por día
- 👤 Tipo de cliente: **Regular** o **Preferencial**

<br>

---

### ⚙️ Cálculo del total

El cálculo se realiza en **4 pasos secuenciales**:

#### 1️⃣ Costo base

```text
Costo base = Cantidad de días × Precio por día
```
#### 2️⃣ Cargo por seguro
``` text
Cargo por seguro = Costo base × 10%   (si Costo base ≤ $300)
Cargo por seguro = Costo base × 7%    (si Costo base > $300)

Subtotal = Costo base + Cargo por seguro
```
#### 3️⃣ Descuento según tipo de cliente
``` text
Descuento = Subtotal × 4%   (si el cliente es Regular)
Descuento = Subtotal × 8%   (si el cliente es Preferencial)
```

#### 4️⃣ Total a pagar
``` text
Total a pagar = Subtotal − Descuento
```
---
<img width="735" height="457" alt="image" src="https://github.com/user-attachments/assets/b86823ba-cfdd-407f-9219-8cecca8b8e93" />
