# Ejercicios Prácticos en VHDL - UNL

## 📌 **Descripción**

Este repositorio contiene una serie de **ejercicios prácticos en VHDL** realizados como parte del curso en la **Universidad Nacional de Loja (UNL)**.  
Los ejercicios están diseñados para comprender y aplicar diferentes estilos de modelado en **VHDL**, incluyendo **estructural, flujo de datos y comportamiento**.

---

## 📂 **Contenido del Repositorio**

- 🔹 **Ejercicios básicos** - Implementación de entidades y puertos en VHDL.  
- 🔹 **Demos de circuitos** - Implementaciones de circuitos lógicos simples y avanzados.  
- 🔹 **Testbenches** - Archivos para verificar el correcto funcionamiento de los módulos.  
- 🔹 **Ejemplos con vectores** - Uso de `bit_vector` y `std_logic_vector` en diferentes escenarios.  
- 🔹 **Modelado estructural** - Ejemplos de interconexión de componentes mediante `port map`.  

---

## 🛠 **Ejercicios Destacados**

### ✅ **DEMO 01: Tabla de Verdad en VHDL**
```vhdl
entity Tabla is
port( A, B, C: in bit;
      F0, F1: out bit);
end Tabla;



---

🛠 **Ejercicios Destacados**

✅ **DEMO 01: Tabla de Verdad en VHDL**

```vhdl
entity Tabla is
port( A, B, C: in bit;
F0, F1: out bit);
end Tabla;
```
📌 **Descripción:** Implementación básica de una tabla de verdad en VHDL.

---

✅ **DEMO 02: Modelado de un Circuito Digital**

```vhdl
entity Circuito is
port (a,b,c,d,f,g,h: in bit; F1: out bit);
end Circuito;
```
📌 **Descripción:** Ejemplo de integración de múltiples señales en un circuito digital.

---

✅ **DEMO 04: Integración de Módulos**

```vhdl
entity Proyecto is
port (A3, A2, A1, A0, B3, B2, B1, B0: in bit;
C3, C2, C1, C0: inout bit;
S3, S2, S1, S0: out bit);
end Proyecto;
```
📌 **Descripción:** Ejemplo de integración de varios módulos utilizando puertos de entrada/salida.

---

🚀 **Ejercicios de Modelado en VHDL**

➡️ **Modelado con Vectores**

```vhdl
entity Proyecto is
port (A, B: in bit_vector(3 downto 0);
C: inout bit_vector(3 downto 0);
S: out bit_vector(3 downto 0));
end Proyecto;
```
📌 **Descripción:** Uso de `bit_vector` para representar señales de múltiples bits.

---

➡️ **Modelado con Procesos**

```vhdl
architecture e_funcional of funcional is
begin
process(A, B)
begin
if A = B then
c <= '1';
else
c <= '0';
end if;
end process;
end e_funcional;
```
📌 **Descripción:** Uso del proceso `if-else` para realizar comparaciones en VHDL.

---

📌 **Cómo Usar estos Ejercicios**

1️⃣ **Abrir los archivos** `.vhdl` en un **simulador de VHDL** como **ModelSim o GHDL**.2️⃣ **Compilar los módulos** y verificar la correcta implementación de las señales.3️⃣ **Ejecutar los testbenches** para validar el comportamiento de los circuitos.

---

📢 **Créditos y Autoría**


- 📌 **Autor:** DavidSotoX (David Alberto Soto Ramón)-  📌 **Universidad:** Universidad Nacional de Loja - UNL- 📌 **Lenguaje:** VHDL

---

💡 **Si encuentras útil este repositorio, no olvides dejar una estrella ⭐ y compartirlo con otros entusiastas de la electrónica digital y el diseño en VHDL!** 🚀
