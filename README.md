# DojoScala

Inicio del Dojo: 8:20 am
Este documento tiene las notas obtenidas en el Dojo.

## Scala

- Lenguaje funcional basado en Java.
- Une POO y funcional.
- Alcance: Pequeños códigos que hacen pequeñas tareas hasta grandes FW.
- Todo es un objeto.
- Utiliza funciones anónimas.
- Tipificado estático: Errores se detectan en tiempo de compilación.
- Maneja dos tipos de variables: Var = Cambia con el tiempo y Val = Constante.

// HOLA MUNDO (NO tengo idea cual es la extensión que maneja scala, supongo que “.scala” XD).

object HolaMundo {
 def main(args: Array[String]) {
  println("¡Hola, mundo!")
 }
}

- Scala = Java (programación) + Lisp (Manejo eficiente: Funcionales).
- Los lenguajes funcionales utilizan el CÁLCULO LAMBDA, una manera mucho más rápida y eficiente de programar. Pero la programación se hace más abstracta.
- Esto nos lleva a aprovechar la programación en paralelo.

- La utilizan (que conozcamos): Twitter, Sony Animation, Siemens.

Lo utilizamos cuando:
- Cuando tenemos que usar clusters (No fue muy claro).
- Si queremos un FW web que no nos sirva para nada (eso dijeron).
- Software de misión crítica.

- FW Play: Scala en web

Aplicaciones reactivas: 
- Aplicaciones con características resilientes (y otras 3 características que no fueron explicadas): recuperarse más fácilmente ante fallos

Ensayando un proyecto:
Descargamos el proyecto: https://github.com/dnetix/DojoScala2
cd al proyecto
sbt
compile
run list
1 (o la opción que quiera)
Si hay un cambio, de nuevo sbt y compile

Vamos a usar Play:

Lo descargamos:
cd ~
wget http://downloads.typesafe.com/typesafe-activator/1.3.2/typesafe-activator-1.3.2-minimal.zip
unzip typesafe-activator-1.3.2-minimal.zip
mv activator-1.3.2-minimal activator
export PATH=~/activator:$PATH
source ~/.bashrc
chmod a+x activator/activator

activator ui
tener paciencia
seleccionamos un proyecto ( el hola mundo de toda la vida)
le indicamos la ruta
Crear proyecto
Click al “botoncito” RUN
En “Code/src/main/scala/” está el código
