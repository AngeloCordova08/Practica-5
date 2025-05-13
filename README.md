<h1>Práctica N°5 - Sistema de Gestión de Concesionaria</h1>

<h2>📘 Universidad Politécnica Salesiana</h2>
<p><strong>Carrera:</strong> Ingeniería en Computación<br>
<strong>Nivel:</strong> Segundo semestre<br>
<strong>Asignatura:</strong> Programación Orientada a Objetos<br>
<strong>Nombre:</strong> Angelo Córdova<br>
<strong>Grupo:</strong> 3</p>

<h2>🎯 Resultado de Aprendizaje</h2>
<p>Construye programas utilizando el paradigma de programación orientada a objetos.</p>

<h3>🧠 Indicador de logro</h3>
<p>Abstrae objetos del mundo real y los modela mediante diagramas de clase.</p>

<h3>⏳ Tiempo estimado:</h3>
<p>2 - 3 horas</p>

<h2>📝 Descripción de la práctica</h2>
<p>Analizar las clases creadas e identificar atributos y métodos. Construir el diagrama de clases respectivo.</p>

<h2>📦 Clases implementadas</h2>

<h3>Clase: <code>cliente</code></h3>
<pre>
- dni: QString
- nombre: QString
- telefono: QString
- direccion: QString
+ Cliente(QString d, QString n, QString t, QString dir)
+ getInfo(): QString
</pre>

<h3>Clase: <code>vehiculo</code></h3>
<pre>
- codigo: QString
- marca: QString
- modelo: QString
- anio: int
- kilometraje: double
- precio: double
+ Vehiculo(QString c, QString m, QString mo, int a, double km, double p)
+ getInfo(): QString
</pre>

<h3>Clase: <code>controlador</code></h3>
<pre>
- QVector<vehiculo> vehiculos
- QVector<cliente> clientes
+ registrarVehiculo(): void
+ registrarCliente(): void
+ consultar(): void
</pre>

<h3>Clase: <code>vista</code></h3>
<pre>
+ mostrarMenu(): void
+ leerTexto(QString): QString
+ leerOpcion(QString): int
+ leerDecimal(QString): double
</pre>

<h2>▶️ Aplicación principal</h2>
<pre>
main.cpp
---------
int main() {
    mostrarMenu();
    ejecutarOpcion();
}
</pre>

<h2>📊 Diagrama de Clases</h2>
<p><img src="diagrama.png" alt="Diagrama de Clases UML" width="600"></p>

<h2>✅ Resultados Obtenidos</h2>
<ul>
  <li>Se creó un sistema funcional con patrón MVC usando Qt y C++</li>
  <li>Se logró separar correctamente el modelo, vista y lógica</li>
  <li>Los registros se almacenan correctamente y se pueden consultar</li>
</ul>

<h2>📌 Conclusión</h2>
<p>La práctica permitió aplicar los principios de programación orientada a objetos de forma modular y organizada, fortaleciendo el uso del patrón MVC y el manejo de clases en C++ usando Qt.</p>

<h2>❗ Dificultades encontradas</h2>
<p>Se presentó dificultad al subir los archivos a GitHub mediante Git Bash. Sin embargo, con apoyo externo se logró resolver y subir correctamente todos los archivos del proyecto.</p>
