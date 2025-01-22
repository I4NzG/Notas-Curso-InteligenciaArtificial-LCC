## Notas de la primera semana 

### **¿Qué es la Inteligencia Artificial?**

Es el desarrollo de agentes racionales... Sin embargo para entender esta respuesta debemos aclarar terminos básicos y elemantales que estaremos usando a lo largo del curso  ya que aún no sabemos que es un agente ni tampoco que significa que este sea racional asi que vamos a aclarar esos terminos.

### **¿Qué es un Agente?**
Se podría decir que un agente es un modelo, y un modelo representa un problema. Por lo tanto, necesitamos definir nuestros problemas para determinar qué acciones debemos tomar. Un agente también puede entenderse como un sistema que percibe su entorno y realiza acciones que afectan dicho entorno, guiado por un conjunto de objetivos.

### **¿Qué es un Entorno?**
Podriamos decir que un entorno es la parte del mundo que el agente puede observar, interpretar y afectar mediante sus sensores y actuadores.
Todos los entornos mantienen ciertas caracteristicas principales:

-**Perceptible:** El agente debe ser capaz de recopilar información del entorno mediante sensores.

-**Interactivo:** Las acciones del agente tienen consecuencias en el entorno.

-**Variable:** El entorno puede cambiar con el tiempo, ya sea de forma independiente o como respuesta a las acciones del agente.

#### **Tipos de entorno**:

Discreto / <span style="color:red;">Continuo </span>

Estático / <span style="color:red;">Dinámico </span>

Observable / <span style="color:red;">Parcialmente	observable </span>

Determinista / <span style="color:red;"> estócastico </span>

Conocido / <span style="color:red;"> Desconocido </span>

Un agente / <span style="color:red;"> Multiagente </span>

Episódico / <span style="color:red;"> Secuencial </span>

### Lo que debe saber  el agente del entorno:

- Medida de desempeño/utilidad (performance)
- Caracteristicas del entorno
- Actuadores
- Sensores

Con esta información ya deberiamos ser capaces de responder la siguiente pregunta:

### **¿Qué es un agente racional?**
Un agente racional es un tipo de agente que toma decisiones basándose en la lógica, el conocimiento disponible y los objetivos que desea alcanzar (OJO: ser racional no significa tener éxito, significa maximizar tu esperanza). Su comportamiento está diseñado para maximizar su desempeño, seleccionando las acciones más adecuadas según la información que percibe de su entorno.

### **Caracteristicas de un agente racional**

- **Percepción**: Es la capacidad del agente para recopilar información sobre el entorno mediante sensores.

- **Conocimiento**: Representación interna que utiliza para modelar el entorno y guiar su toma de decisiones.

- **Razonamiento**: Proceso de evaluación y selección de acciones que maximicen el desempeño esperado.

- **Acción**: Ejecución de las decisiones tomadas mediante actuadores o comandos.

- **Medida de desempeño**: Criterio que determina qué tan efectivas han sido las acciones del agente para alcanzar sus objetivos.

- **Objetivos**: Metas o fines que el agente busca cumplir para orientar su comportamiento.