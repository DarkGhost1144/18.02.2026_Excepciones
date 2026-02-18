UD 10: Control y Manejo de Excepciones:

    1. Escribe un programa Java que permita calcular el área de un triángulo:
        ÁreaTriángulo = (base*altura)/2
        La lectura de base y altura será por teclado usando Scanner. Considere que el usuario podría
        ingresar de forma errónea los datos como letras, espacios en blanco, simboles especiales…. Para
        evitar errores debe agregar a su programa el manejo de excepciones try, catch. Considere todas las
        posibilidades de fallo.
        Implementa el ejercicio anterior viendo que tipo de excepción lanza Java cuando introducimos un
        carácter erróneo (que no sea un número) y, a continuación, captura dicha excepción y lanza el
        mensaje apropiado al usuario.
        
    2. Excepciones propias. Diseña la clase Persona con los atributos DNI y nombre. 
        Crea su constructor, getters, setters y redefine toString. Crea otra clase llamada ListaPersona con el
        atributo listaP que será un array de 10 personas. Esta clase tendrá un método anadirPersona, que
        recibe como parámetro un objeto de la clase Persona y lo guarda en el array, en la posición que
        nos indique el atributo posición.
        El método anadirPersona lanzará una excepción de la clase ExcepcionArrayLleno cuando no
        podamos seguir introduciendo objetos Persona en el array listaP. Esta excepción dará lugar a que
        se muestre el mensaje “Imposible añadir, array lleno”.
        Debes por tanto crear la clase ExcepcionArrayLleno.
        
    3. A partir de la última práctica de JAVITOS, crea 3 excepciones propias:
        • ClienteExistenteException. A la hora de dar de alta a un cliente, si ya existe en la lista de
        clientes (existe un cliente con el mismo DNI), debe lanzarse esta excepción. La
        excepción debe capturarse en el método main de la clase Principal y notificar al usuario
        a través de un mensaje de texto por consola.
        • AlojamientoExistenteException. A la hora de dar de alta a un alojamiento, si ya existe
        en la lista de alojamientos (existe un alojamiento con el mismo nombre), debe lanzarse
        esta excepción. La excepción debe capturarse en el método main de la clase Principal y
        notificar al usuario a través de un mensaje de texto por consola.
        • DniNoValidaException. A la hora de dar de alta un nuevo cliente, si el dni introducido
        no cumple el patrón correspondiente, debe lanzarse esta excepción. La excepción debe
        capturarse en el método main de la clase Principal y notificar al usuario a través de un
        mensaje de texto por consola.
        • EmailNoValidoException. Similar al anterior, pero con el patrón correspondiente del
        email del cliente. 
