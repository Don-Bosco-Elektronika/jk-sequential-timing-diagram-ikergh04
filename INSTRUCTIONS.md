# 🛠️ Zirkuitu Sekuentzialen Kronograma

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## 📌 Ariketa

**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| ? | ?             | ? | ? |  

**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| ? | ?             | ? | ? |  

---

## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

---

## 🔲 Simulatzeko Zirkuituak




---

## 🔲 Kronogramaren Emaitza
<img width="602" height="160" alt="Captura de pantalla 2026-01-21 131448" src="https://github.com/user-attachments/assets/72cc9811-000b-4033-989f-3c131aada99c" />
<img width="641" height="168" alt="Captura de pantalla 2026-01-21 131509" src="https://github.com/user-attachments/assets/66d7a9ee-8156-4674-8d79-28312d401d46" />

---


## 🔲 Kronogramaren Kodea
Ejercicio 2: JK flanco ascendente

{signal: [

  {name: 'clk', wave: 'P........', period: 2},
  
  {name: 'J',   wave: '0101..0101.010.1.0'},
  
  {name: 'K',   wave: '1..0..101...01.01.'},
  
  {},
  
  {name: 'Q',   wave: '0.1.0.10.1...0.1.0'},
  
  {name: '-Q',  wave: '1.0.1.01.0...1.0.1'}

]}

Ejercicio 2: JK flanco descendente

{signal: [

  {name: 'clk', period: 3, wave: 'N.....'},
  
  {name: 'J', wave: '0101..0101.0..1.0'},
  
  {name: 'K', wave: '1...0..1.0..1..01'},
  
  {},
  
  {name: 'Q', wave: '0..1..0..1..1..0..'},
  
  {name: '-Q', wave: '1..0..1..0..0..1..'}

]}

---


## 📤 Entrega / Igo / Upload  

➡️ **Instrucciones:**  

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.



