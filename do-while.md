##Robot chat

El robot que cotorrea:
Se requiere que un robot-chat inicie la conversación con el usuario.
a partir del saludo el robot tendra que preguntar "algo" al usuario y dependiendo si el usuario el responde con la palabra "clave" el robot tendra que decir si continua con un monologo po se despide.

Nuestro SDK nos explica que podemos usar las siguientes funcionalidades.


    Saludar()
    PreguntarTemaRandom()
    Monologo()
    Despedirse()

inicio
    Saludar()
    imprimir '¿en que te puedo ayudar?'
    Leer y guardar Respuesta
    flag=0
    mientras (Respuesta != 'adios' o Respuesta != 'sayonara' o Respuesta != 'nos vemos') 
    inicio mietras

        Si RespuestaRamdon(Respuesta) = verdadero entoces
            PreguntaRandome
            

   fin mientras
    
    if else

    do while 
    Despedirse()

fin

#Respuesta de la maestra

inicio
    Hacer
    inicio-hacer
        Saludar()
        PreguntaRandom()
        Leer y guardar Respuesta
        si (respuesta != Salir)
            monologo()
    fin-hacer
    mientras (Respuesta != salir)
    Despedirse()
fin