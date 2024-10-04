fun main(args: Array<String>) {
    println ("ingrese la primera calificacion")
    val cal1=readlnOrNull()?.toDoubleOrNull()?:0.0


    println ("ingrese la segunda calificacion")
    val cal2=readlnOrNull()?.toDoubleOrNull()?:0.0


    println ("ingrese la tercera calificacion")
    val cal3=readlnOrNull()?.toDoubleOrNull()?:0.0

    val promedio=(cal1+cal2+cal3)/3

    println ("el promdeio es: " + promedio)

}
