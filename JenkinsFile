pipeline
{
    agent any
    stages
    {
        stage("Dias de la semana")
        {
            steps
            {
                script
                {
                    mapa= ("Lunes, Martes, Miercoles, Jueves, Viernes, Sabado, Domingo")
                    println "La semana consta de los siguientes días: " + mapa
                }
            }
        }
	stage("Que día es hoy")
	{
	    steps
            {
                script
                {
                    dia = new Date().getDay()
                    dia_actual = new Date()
                    mapa= [1: "Lunes", 2:"Martes", 3: "Miercoles", 4:"Jueves", 5:"Viernes", 6: "Sabado", 7:"Domingo"]
                    println "El dia actual es: " + mapa[dia]
                }
            }
	}
    }
}
