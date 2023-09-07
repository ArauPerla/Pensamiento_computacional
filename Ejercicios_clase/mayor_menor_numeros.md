# 3 numeros de mayor a menor

## PSInt

### Tarea
    Algoritmo numeros_mayor_a_menor
    	Definir num_1, num_2, num_3 Como Real
    	Escribir "Introduce primer numero"
    	Leer num_1
    	Escribir "Introduce segundo numero"
    	Leer num_2
    	Escribir "Introduce tercer numero"
    	Leer num_3
    	Si num_1 > num_2 y num_2 > num_3 Entonces
    		may = num_1
    	SiNo
    		Si num_2 > num_1 y num_2 > num_3 Entonces
    			may = num_2
    		SiNo 
    			may = num_3
    		FinSi
    	FinSi
    	Si num_1 < num_2 y num_2 < num_3 Entonces
    		men = num_1
    	SiNo
    		Si num_2 < num_1 y num_2 < num_3 Entonces
    			men = num_2
    		SiNo
    			men = num_3
    		FinSi
    	FinSi
    	med = ((num_1 + num_2 + num_3) - (may + men))
    	Escribir "Mayor =", " ", may, " ", "Medio =", " ", med, " ", "Menor =", " ", men
    FinAlgoritmo

## Clase

    Algoritmo clase_numeros_mayor_a_menor
    	Definir num_1, num_2, num_3, may, med, men Como Real
    	Escribir "Introduce primer numero"
    	Leer num_1
    	Escribir "Introduce segundo numero"
    	Leer num_2
    	Escribir "Introduce tercer numero"
    	Leer num_3
    	Si num_1 < num_2 y num_1 < num_3 Entonces
    		Si num_2 < num_3 Entonces
    			Escribir num_1, num_2, num_3
    		SiNo
    			Escribir num_1, num_3, num_2
    		FinSi
    	SiNo
    		Si num_2 < num_1 y num_2 < num_3 Entonces
    			Si num_1 < num_3 Entonces
    				Escribir num_2, num_1, num_3
    			SiNo
    				Escribir num_2, num_3, num_1
    			FinSi
    	    SiNo 
    			Si num_3 < num_1 y num_3 < num_2 Entonces
    			  Si num_1< num_2 entonces 
    			    Escribir num_3, num_1, num_2
    		      SiNo
    				  Escribir num_3, num_2, num_1
    			  FinSi
    		    FinSi
    		FinSi
    	FinSi
    FinAlgoritmo
