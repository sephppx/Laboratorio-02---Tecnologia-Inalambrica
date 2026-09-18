# Laboratorio 02 - Tecnología Inalámbrica

## Uso del Analizador de Espectros

**Integrantes:**

- Felipe Bustos López
- Francisco Polanco Alfaro

---

## Descripción

En este laboratorio se realizó una caracterización experimental de señales presentes en el espectro radioeléctrico mediante el uso de un analizador de espectros.

La experiencia tuvo como objetivo identificar y analizar señales de radio FM, considerando parámetros como frecuencia central, potencia recibida, ancho de banda y relación señal a ruido (SNR).

Además, se realizó un análisis espectral de señales correspondientes a televisión VHF y UHF, comparando la ocupación del espectro observada en ambos rangos de frecuencia.

---

## Equipamiento utilizado

Para realizar las mediciones se utilizaron los siguientes elementos:

- Analizador de espectros **Rohde & Schwarz FSH4**.
- Antena para la captura de señales de radiofrecuencia.
- Cables y conectores de radiofrecuencia.
- Computador para el registro y análisis de los resultados.

---

## Actividades realizadas

### 1. Análisis de señales de radio FM

Se realizó un barrido de la banda comercial de radio FM, aproximadamente entre 88 MHz y 108 MHz.

Durante la experiencia se identificaron ocho señales y se registraron los siguientes parámetros:

- Frecuencia central.
- Potencia recibida en dBm.
- Potencia equivalente en dBµV.
- Ancho de banda.
- Relación señal a ruido (SNR).

Las señales analizadas fueron:

| Frecuencia | Emisora |
|---:|---|
| 88.1 MHz | Radio Imagina |
| 89.7 MHz | Radio Duna |
| 91.7 MHz | ADN Radio |
| 94.1 MHz | Rock & Pop |
| 95.9 MHz | La Metro FM |
| 99.3 MHz | Radio Carolina |
| 101.3 MHz | Radio Corazón |
| 104.9 MHz | FM Plus |

Las capturas utilizadas como evidencia se encuentran en:

`Evidencia/Radio FM/`

---

### 2. Análisis de televisión VHF y UHF

Se analizaron los canales indicados en la actividad práctica:

- **Canal 13 VHF**, correspondiente al rango de 210 a 216 MHz, con frecuencia central aproximada de 213 MHz.
- **Canal 24 UHF**, correspondiente al rango de 530 a 536 MHz, con frecuencia central aproximada de 533 MHz.

Para el canal 13 VHF no se identificó una señal de televisión claramente diferenciable del piso de ruido durante la medición.

Para el canal 24 UHF se observó una señal de banda ancha dentro del rango correspondiente al canal.

Las capturas utilizadas como evidencia se encuentran en:

`Evidencia/VHF:UHF/`

---

## Resultados

### Radio FM

Durante la experiencia se identificaron ocho señales dentro de la banda de radiodifusión FM.

Los niveles de potencia recibida se encontraron entre:

**-113.3 dBm y -107.0 dBm**

La diferencia entre la señal de mayor y menor potencia registrada fue de:

**6.3 dB**

La relación señal a ruido presentó valores entre:

**18.4 dB y 31.8 dB**

El ancho de banda medido presentó valores entre:

**50.794 kHz y 138.095 kHz**

Las mediciones completas se encuentran registradas en el informe del laboratorio.

---

### Televisión VHF

Para el análisis del canal 13 VHF se configuró el analizador alrededor de:

**213 MHz**

Los marcadores registrados fueron:

- **M1:** 211.253968 MHz, -99.9 dBm.
- **M2:** 215.730159 MHz, -96.7 dBm.

Durante la medición no se identificó una señal de televisión claramente diferenciable del piso de ruido.

---

### Televisión UHF

Para el análisis del canal 24 UHF se configuró el analizador alrededor de:

**533 MHz**

Los marcadores registrados fueron:

- **M1:** 529.936508 MHz, -96.8 dBm.
- **M2:** 536.444444 MHz, -96.3 dBm.

La medición permitió observar una señal de banda ancha dentro del rango correspondiente al canal.

La diferencia de frecuencia indicada por el analizador entre los marcadores fue:

**D3 = 3.428571 MHz**

con una diferencia de nivel de:

**19.4 dB**

---

## Evidencia experimental

La carpeta `Evidencia` contiene las capturas obtenidas directamente durante la experiencia de laboratorio.

Las imágenes se organizan de acuerdo con el tipo de medición realizada:

```text
Evidencia/
│
├── Radio FM/
│   ├── Radio Imagina.jpeg
│   ├── Radio Duna.jpeg
│   ├── ADN Radio.jpeg
│   ├── Rock & Pop.jpeg
│   ├── La Metro FM.jpeg
│   ├── Radio Carolina.jpeg
│   ├── Radio Corazon.jpeg
│   └── FM Plus.jpeg
│
└── VHF_UHF/
    ├── Canal13 VHF.jpeg
    └── Canal24UHF.jpeg
```

Estas imágenes corresponden a las capturas realizadas con el analizador de espectros y permiten respaldar los valores utilizados en las tablas y el análisis del informe.

---

## Informe

El informe completo del laboratorio se encuentra en:

`LAB02_Tecnologia_Inalambrica.pdf`

El documento contiene:

- Introducción.
- Marco teórico.
- Equipamiento utilizado.
- Metodología.
- Análisis de señales de radio FM.
- Tablas de resultados.
- Conversión de dBm a dBµV.
- Análisis de potencia y SNR.
- Análisis del canal 13 VHF.
- Análisis del canal 24 UHF.
- Comparación entre VHF y UHF.
- Conclusiones.
- Referencias.

---

## Organización del repositorio

La estructura final del repositorio es:

```text
Laboratorio-02-Tecnologia-Inalambrica/
│
├── README.md
│
├── LAB02_Tecnologia_Inalambrica.pdf
│
└── Evidencia/
    │
    ├── Radio FM/
    │   ├── Radio Imagina.jpeg
    │   ├── Radio Duna.jpeg
    │   ├── ADN Radio.jpeg
    │   ├── Rock & Pop.jpeg
    │   ├── La Metro FM.jpeg
    │   ├── Radio Carolina.jpeg
    │   ├── Radio Corazon.jpeg
    │   └── FM Plus.jpeg
    │
    └── VHF_UHF/
        ├── Canal13 VHF.jpeg
        └── Canal24UHF.jpeg
```

Los archivos generados automáticamente por macOS, como `.DS_Store` y la carpeta `__MACOSX`, no forman parte de la evidencia del laboratorio y no se incluyen en el repositorio.

---

## Repositorio

El informe y las evidencias experimentales se encuentran disponibles en el repositorio de GitHub:

[Repositorio de GitHub](https://github.com/sephppx/Laboratorio-02-Tecnologia-Inalambrica)

---

## Autores

**Felipe Bustos López**

**Francisco Polanco Alfaro**

**Tecnología Inalámbrica, 2026**
