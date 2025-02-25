# MARCO-NORMATIVO-DE-LA-CALIDAD-DE-AGUA
MARCO NORMATIVO DE LA CALIDAD DE AGUA, AGUAS RESIDUALES Y VALORES MAXIMOS EN EL PERU
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Normativa de Calidad de Agua en Perú</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: #1e3a8a;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 15px;
        }

        nav ul li button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 1em;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        nav ul li button:hover {
            background-color: #45a049;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #1e3a8a;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        h2 {
            color: #1e3a8a;
        }

        ul {
            padding-left: 20px;
        }

        .normativa {
            background-color: #e2e8f0;
            padding: 10px;
            border-radius: 5px;
            margin: 10px 0;
        }

        .normativa h3 {
            margin: 0;
            color: #334155;
        }

        .normativa p {
            margin: 5px 0;
        }

        /* Estilo de la línea de tiempo */
        .timeline {
            position: relative;
            padding: 10px 0;
            margin-top: 20px;
        }

        .timeline-item {
            position: relative;
            margin-left: 20px;
            margin-bottom: 15px;
        }

        .timeline-item:before {
            content: '';
            position: absolute;
            left: -7px;
            top: 0;
            height: 100%;
            width: 2px;
            background-color: #1e3a8a;
        }

        .timeline-content {
            background-color: white;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 320px;
            margin-left: 40px;
        }

        .timeline-date {
            font-weight: bold;
            color: #1e3a8a;
        }

        .timeline-date-sub {
            font-style: italic;
            color: #555;
        }

    </style>
    <script>
        function mostrarInfo(info) {
            let contenido = document.getElementById('contenido');
            if (info === 'calidad-agua') {
                contenido.innerHTML = `
                    <h2>Marco Normativo de la Calidad del Agua en Perú</h2>
                    <p>La calidad del agua es un factor fundamental para garantizar la salud pública y el bienestar de la población. En Perú, se han establecido diversas normativas que buscan asegurar que el agua destinada al consumo humano, industrial y recreacional cumpla con los estándares más altos de seguridad. Las leyes y regulaciones están diseñadas para prevenir la contaminación del agua y fomentar la conservación de los recursos hídricos en todo el país.</p>
                    <p><strong>Conceptos clave:</strong></p>
                    <ul>
                        <li><strong>Calidad del agua:</strong> La calidad del agua es un concepto integral que engloba las características físicas, químicas, biológicas y microbiológicas del agua, que determinan su aptitud para diferentes usos, tales como consumo humano, uso agrícola, industrial, recreacional o para la conservación de ecosistemas acuáticos. Para asegurar que el agua cumpla con estos estándares, se deben medir diversos parámetros como el pH, turbidez, oxígeno disuelto, entre otros.</li>
                        <li><strong>Aguas residuales:</strong> Las aguas residuales son aguas que han sido utilizadas en procesos domésticos, industriales, comerciales, o agrícolas, y que se han cargado con contaminantes, lo que puede afectar negativamente la calidad del agua en los cuerpos receptores. Estas aguas deben ser tratadas para eliminar o reducir los contaminantes antes de ser devueltas al medio ambiente.</li>
                        <li><strong>Parámetros de calidad:</strong> Los parámetros de calidad son las mediciones que se realizan para evaluar el estado físico, químico, biológico y microbiológico del agua. Estos parámetros permiten identificar la presencia de contaminantes y determinar si el agua cumple con los estándares requeridos para su uso específico.
                    <p><strong>Leyes relevantes:</strong></p>
                    <ul>
                        <li><strong>Ley N° 29338 - Ley de Recursos Hídricos (2009):</strong> Establece el marco normativo para la gestión sostenible de los recursos hídricos en el país, promoviendo el uso eficiente y la conservación del agua, y creando la Autoridad Nacional del Agua (ANA).</li>
                        <li><strong>Decreto Supremo N° 002-2015-MINAM:</strong> Regula los valores máximos admisibles para la calidad del agua en diferentes contextos, desde el agua potable hasta la de uso recreacional e industrial.</li>
                        <li><strong>Decreto Supremo N° 003-2015-MINAM:</strong> Establece las normas para el tratamiento y disposición de aguas residuales, buscando minimizar el impacto ambiental de las actividades humanas sobre los cuerpos de agua.</li>
                    </ul>
                `;
 } else if (info === 'Marco Normativo de la Calidad del Agua en Perú') {
                contenido.innerHTML = `   
                <h2>Marco Normativo de la Calidad del Agua en Perú</h2>
                <p>La calidad del agua es un factor fundamental para garantizar la salud pública y el bienestar de la población. En Perú, se han establecido diversas normativas que buscan asegurar que el agua destinada al consumo humano, industrial y recreacional cumpla con los estándares más altos de seguridad. Las leyes y regulaciones están diseñadas para prevenir la contaminación del agua y fomentar la conservación de los recursos hídricos en todo el país.</p>
                <p><strong>Conceptos clave:</strong></p>
                <ul>
                    <li><strong>Calidad del agua:</strong> La calidad del agua es un concepto integral que engloba las características físicas, químicas, biológicas y microbiológicas del agua, que determinan su aptitud para diferentes usos, tales como consumo humano, uso agrícola, industrial, recreacional o para la conservación de ecosistemas acuáticos. Para asegurar que el agua cumpla con estos estándares, se deben medir diversos parámetros como el pH, turbidez, oxígeno disuelto, entre otros.</li>
                    <li><strong>Aguas residuales:</strong> Las aguas residuales son aguas que han sido utilizadas en procesos domésticos, industriales, comerciales, o agrícolas, y que se han cargado con contaminantes, lo que puede afectar negativamente la calidad del agua en los cuerpos receptores. Estas aguas deben ser tratadas para eliminar o reducir los contaminantes antes de ser devueltas al medio ambiente.</li>
                    <li><strong>Parámetros de calidad:</strong> Los parámetros de calidad son las mediciones que se realizan para evaluar el estado físico, químico, biológico y microbiológico del agua. Estos parámetros permiten identificar la presencia de contaminantes y determinar si el agua cumple con los estándares requeridos para su uso específico.</li>
                </ul>
                <p><strong>Leyes relevantes:</strong></p>
                <ul>
                    <li><strong>Ley N° 29338 - Ley de Recursos Hídricos (2009):</strong> Establece el marco normativo para la gestión sostenible de los recursos hídricos en el país, promoviendo el uso eficiente y la conservación del agua, y creando la Autoridad Nacional del Agua (ANA).</li>
                    <li><strong>Decreto Supremo N° 002-2015-MINAM:</strong> Regula los valores máximos admisibles para la calidad del agua en diferentes contextos, desde el agua potable hasta la de uso recreacional e industrial.</li>
                    <li><strong>Decreto Supremo N° 003-2015-MINAM:</strong> Establece las normas para el tratamiento y disposición de aguas residuales, buscando minimizar el impacto ambiental de las actividades humanas sobre los cuerpos de agua.</li>
                </ul>
                `;
     
            } else if (info === 'Instituciones encargadas de la regulacion del agua en Perú') {
    contenido.innerHTML = `
        <h2>Instituciones encargadas de la regulación del agua en Perú</h2>
        <h4>1. Nivel Nacional (Gobierno Central)</h4>
        <ul>
            <li><strong>Autoridad Nacional del Agua (ANA):</strong> Organismo rector en la gestión de los recursos hídricos. Adscrito al Ministerio de Desarrollo Agrario y Riego (MIDAGRI). Administra, regula, fiscaliza y supervisa el uso del agua.</li>
            <li><strong>Ministerio del Ambiente (MINAM):</strong> Regula la calidad del agua y la gestión ambiental. Responsable de la protección de ecosistemas hídricos.</li>
            <li><strong>Ministerio de Vivienda, Construcción y Saneamiento (MVCS):</strong> Encargado de políticas de agua potable y saneamiento. Supervisa a las empresas prestadoras de servicios de saneamiento (EPS).</li>
            <li><strong>Ministerio de Salud (MINSA):</strong> Asegura la calidad del agua potable para el consumo humano. Supervisa riesgos sanitarios relacionados con el agua.</li>
            <li><strong>Superintendencia Nacional de Servicios de Saneamiento (SUNASS):</strong> Regula y supervisa las tarifas y calidad de los servicios de agua potable y saneamiento.</li>
        </ul>
        <h4>2. Nivel Regional y Local</h4>
        <ul>
            <li><strong>Gobiernos Regionales:</strong> Gestionan proyectos de infraestructura hídrica en sus jurisdicciones.</li>
            <li><strong>Gobiernos Locales (Municipalidades):</strong> Encargados de la distribución del agua potable y alcantarillado en zonas urbanas y rurales.</li>
            <li><strong>Empresas Prestadoras de Servicios de Saneamiento (EPS):</strong> Empresas públicas y privadas que operan en cada ciudad para abastecer de agua potable y saneamiento.</li>
            <li><strong>Juntas de Usuarios de Agua:</strong> Organizaciones de agricultores que administran el uso del agua en riego.</li>
            <li><strong>Comités de Agua y Saneamiento Rural (JASS):</strong> Gestionan el acceso al agua en comunidades rurales.</li>
        </ul>
    `;
} else if (info === 'aguas-residuales') {
                contenido.innerHTML = `
                    <h2>Calidad de Aguas Residuales en Perú</h2>
                    <p>Las aguas residuales son aquellas que han sido utilizadas en diversos procesos y actividades humanas, como la industria, la agricultura y los hogares. La correcta gestión de estas aguas es fundamental para prevenir la contaminación de los cuerpos de agua y proteger la salud pública. Perú ha implementado diversas normativas que exigen el tratamiento de aguas residuales antes de su liberación al ambiente.</p>
                    <p>Las aguas residuales se dividen en dos tipos: las domésticas y las industriales. Las aguas residuales domésticas provienen de actividades del hogar (como baños, cocinas y lavanderías), mientras que las industriales provienen de fábricas, plantas de procesamiento y otras actividades productivas. Ambas requieren tratamiento adecuado antes de ser vertidas a los ríos o al mar.</p>
                    <p><strong>Normativa relevante:</strong></p>
                    <ul>
                        <li><strong>Decreto Supremo N° 003-2015-MINAM:</strong> Establece los requisitos técnicos para el tratamiento de aguas residuales industriales y municipales. Los estándares de calidad incluyen parámetros como el pH, la demanda bioquímica de oxígeno (DBO) y los sólidos suspendidos totales (SST).</li>
                        <li><strong>Normas Internacionales:</strong> Además de la legislación nacional, Perú también sigue las recomendaciones de organismos internacionales como la OMS y la Organización Panamericana de la Salud (OPS), que proporcionan directrices para el tratamiento y disposición de aguas residuales.</li>
                    </ul>
                `;
            } else if (info === 'valores-admisibles') {
                contenido.innerHTML = `
                    <h2>Valores Máximos Admisibles en Perú</h2>
                    <p>Los valores máximos admisibles (VMA) son los límites establecidos para diversos parámetros de la calidad del agua que garantizan su seguridad para distintos usos. En Perú, estos valores están regulados por el Decreto Supremo N° 002-2015-MINAM y se aplican a distintos tipos de agua, como agua potable, de consumo industrial y de recreación.</p>
                    <p><strong>Principales parámetros y sus valores admisibles:</strong></p>
                    <ul>
                        <li><strong>pH:</strong> Entre 6.5 y 8.5 para agua potable, agua de riego y agua recreacional.</li>
                        <li><strong>Turbidez:</strong> Menor a 5 NTU para agua potable y menor a 50 NTU para agua de riego.</li>
                        <li><strong>Oxígeno disuelto:</strong> Superior a 5 mg/L para agua potable y para la mayoría de los usos industriales.</li>
                        <li><strong>Coliformes fecales:</strong> Menor a 1000 NMP/100 mL para agua potable y agua recreacional.</li>
                        <li><strong>Metales pesados (como plomo, cadmio, mercurio):</strong> Las concentraciones de estos elementos deben ser mínimas, con valores máximos establecidos dependiendo del tipo de agua.</li>
                    </ul>
                    <p>El cumplimiento de estos valores es esencial para proteger la salud humana y el medio ambiente, así como para garantizar la seguridad de los recursos hídricos en el país.</p>
                `;
            } else if (info === 'linea-tiempo') {
                contenido.innerHTML = `
                    <h2>Línea de Tiempo de las Normativas Clave</h2>
                    <div class="timeline">
                        <div class="timeline-item">
                            <div class="timeline-date">2009</div>
                            <div class="timeline-content">
                                <h3>Ley N° 29338 - Ley de Recursos Hídricos</h3>
                                <p><span class="timeline-date-sub">Promulgada el 27 de enero de 2009.</span></p>
                                <p>La Ley N° 29338 establece el marco legal para la gestión sostenible de los recursos hídricos en Perú, promoviendo la participación ciudadana y la eficiencia en el uso del agua. Además, crea la Autoridad Nacional del Agua (ANA) como organismo rector de la gestión hídrica.</p>
                            </div>
                        </div>
                        <div class="timeline-item">
                            <div class="timeline-date">2015</div>
                            <div class="timeline-content">
                                <h3>Decreto Supremo N° 002-2015-MINAM</h3>
                                <p><span class="timeline-date-sub">Promulgado el 11 de marzo de 2015.</span></p>
                                <p>Este decreto establece los valores máximos admisibles para diversos parámetros de calidad del agua, como pH, turbidez, coliformes fecales, entre otros. Además, regula la calidad del agua utilizada en diferentes sectores, desde el consumo humano hasta el uso industrial.</p>
                            </div>
                        </div>
                        <div class="timeline-item">
                            <div class="timeline-date">2015</div>
                            <div class="timeline-content">
                                <h3>Decreto Supremo N° 003-2015-MINAM</h3>
                                <p><span class="timeline-date-sub">Promulgado el 11 de marzo de 2015.</span></p>
                                <p>El Decreto Supremo N° 003 regula el tratamiento y disposición de aguas residuales en el país. Establece los requisitos técnicos y los parámetros de calidad para el tratamiento de aguas residuales industriales y municipales, buscando minimizar el impacto ambiental.</p>
                            </div>
                        </div>
                    </div>
                `;
            } else if (info === 'moquegua') {
                contenido.innerHTML = `
                    <h2>Contaminación del Agua en Moquegua</h2>
                    <p>La región de Moquegua, ubicada en el sur de Perú, ha enfrentado varios problemas relacionados con la contaminación del agua. En especial, los ríos y fuentes hídricas en la región han sido afectados por actividades industriales, como la minería. Un caso relevante es el incidente de contaminación de las aguas del río Moquegua, provocado por el vertido de metales pesados provenientes de una mina cercana.</p>
                    <p><strong>Caso de contaminación del río Moquegua:</strong></p>
                    <ul>
                        <li><strong>Descripción:</strong> En el año 2012, la empresa minera Cerro Verde, ubicada en la región, fue señalada por la contaminación de los ríos cercanos debido a vertidos industriales. Las autoridades locales y la población afectada exigieron un plan de remediación ambiental.</li>
                        <li><strong>Respuesta:</strong> Tras las denuncias, el gobierno peruano, a través de la Autoridad Nacional del Agua (ANA), realizó inspecciones en la zona y ordenó a la empresa minera la implementación de medidas correctivas, como la instalación de sistemas de tratamiento de aguas y la restitución de los ecosistemas afectados.</li>
                        <li><strong>Resultados:</strong> La empresa minera implementó planes de recuperación del recurso hídrico, y las fuentes de agua afectadas fueron sometidas a un proceso de recuperación con monitoreos periódicos. Las comunidades también recibieron apoyo para la mejora de sus fuentes de agua potable.</li>
                    </ul>
                `;
            }
        }
    </script>
</head>
<body>

    <header>
        <h1>Normativa de Calidad del Agua en Perú</h1>
        <nav>
            <ul>
                <li><button onclick="mostrarInfo('Instituciones encargadas de la regulacion del agua en Perú')">Instituciones encargadas de la regulación del agua en Perú</button></li>
		<li><button onclick="mostrarInfo('calidad-agua')">Calidad del Agua</button></li>
                <li><button onclick="mostrarInfo('aguas-residuales')">Aguas Residuales</button></li>
                <li><button onclick="mostrarInfo('valores-admisibles')">Valores Admisibles</button></li>
                <li><button onclick="mostrarInfo('linea-tiempo')">Línea de Tiempo</button></li>
                <li><button onclick="mostrarInfo('moquegua')">Moquegua y Casos</button></li>
            </ul>
        </nav>
    </header>

    <section id="contenido">
        <h2>Bienvenido a la Información sobre la Normativa de Calidad de Agua en Perú</h2>
        <p>Este es un resumen sobre las principales normativas que rigen la calidad del agua y las aguas residuales en Perú. Estas leyes buscan asegurar que tanto el agua potable como las aguas residuales sean manejadas de manera segura, protegiendo la salud humana y el medio ambiente.</p>
    </section>

    <footer>
        
        <p>Desarrollado por alumnos de la Universidad Nacional de Moquegua de la carrera profesional de Ingenieria Ambiental [Renato D. Segura Arias y Luren A. Lazo Quispe] - 2025</p>
    </footer>
</body>
</html>
