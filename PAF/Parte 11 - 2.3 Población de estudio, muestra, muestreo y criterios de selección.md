## 2.3 Población de estudio, muestra, muestreo y criterios de selección

### 2.3.1. Población de estudio

La población de estudio estará conformada por los registros energéticos generados en plantas agroindustriales de la región Lambayeque, relacionados con el funcionamiento de equipos eléctricos utilizados en actividades de procesamiento, secado, refrigeración, molienda, almacenamiento o transformación de productos agrícolas. Estos registros incluyen variables como corriente, voltaje, potencia eléctrica, consumo energético, fecha, hora, estado operativo de los equipos y eventos anómalos asociados al uso de energía.

La unidad principal de análisis será el registro energético generado por equipos o procesos agroindustriales durante un intervalo temporal determinado. De manera complementaria, se considerará información técnica proporcionada por personal vinculado con operación, mantenimiento, supervisión energética o gestión de costos, siempre que dicha información contribuya a contextualizar el funcionamiento de los procesos productivos.

### 2.3.2. Muestra

La muestra estará conformada por registros energéticos que cumplan condiciones mínimas de calidad, completitud, pertinencia y compatibilidad con el procesamiento computacional. Estos registros serán utilizados para construir el dataset experimental, entrenar los modelos de Machine Learning y evaluar la capacidad del sistema inteligente para predecir y optimizar el consumo energético.

La cantidad exacta de registros dependerá de la disponibilidad de datos otorgados por la planta agroindustrial o por la fuente energética seleccionada. En caso de contar con un volumen suficiente de información, los datos serán divididos aproximadamente en 80 % para entrenamiento y 20 % para prueba. Esta separación permitirá comparar el comportamiento del modelo frente a datos usados durante el entrenamiento y frente a datos no observados previamente. Este criterio es coherente con estudios de predicción energética basados en datos masivos, como el Building Data Genome Project 2, donde se organizan mediciones horarias de consumo para tareas de modelado y predicción [M5B9][29].

### 2.3.3. Muestreo

El tipo de muestreo será no probabilístico por conveniencia, debido a que los registros energéticos serán seleccionados según su disponibilidad, acceso autorizado, estructura, calidad y utilidad para el desarrollo del sistema inteligente. Esta estrategia resulta pertinente para una investigación aplicada y experimental, ya que el objetivo principal es evaluar el desempeño del sistema basado en Machine Learning a partir de datos reales o técnicamente representativos del contexto agroindustrial.

Para el personal que participe brindando información contextual o técnica, también se aplicará muestreo no probabilístico por conveniencia. Se considerará a trabajadores disponibles que cumplan los criterios de inclusión y que tengan relación directa con la operación, mantenimiento, supervisión o gestión energética de los procesos agroindustriales.

### 2.3.4. Criterios de selección

#### a. Criterios de inclusión

Se incluirán registros y participantes que cumplan con las siguientes características:

- Registros energéticos relacionados con plantas agroindustriales de Lambayeque.
- Datos que contengan variables medibles como corriente, voltaje, potencia eléctrica, consumo energético, fecha u hora de registro.
- Registros estructurados en formatos compatibles con procesamiento computacional, como CSV, JSON, hojas de cálculo o bases de datos.
- Información energética proveniente de sensores IoT, medidores inteligentes, reportes técnicos o registros operativos verificables.
- Datos con suficiente completitud para entrenamiento, prueba y evaluación de modelos de Machine Learning.
- Personal vinculado con producción, mantenimiento, operación de maquinaria, supervisión energética o gestión de costos.
- Participantes que acepten brindar información contextual o técnica mediante consentimiento informado, cuando corresponda.

#### b. Criterios de exclusión

Se excluirán registros y participantes que presenten las siguientes condiciones:

- Registros energéticos incompletos, corruptos, duplicados o sin identificación temporal.
- Datos que no correspondan al contexto agroindustrial o que no estén relacionados con consumo energético.
- Mediciones con inconsistencias técnicas que impidan su procesamiento o análisis.
- Registros sin variables suficientes para entrenamiento o evaluación del modelo predictivo.
- Información sensible de empresas o trabajadores que no cuente con autorización para uso académico.
- Personas sin relación directa con procesos agroindustriales, operación de equipos, mantenimiento, supervisión energética o gestión de costos.
- Participantes que no acepten formar parte del estudio o que no otorguen consentimiento informado cuando sea requerido.