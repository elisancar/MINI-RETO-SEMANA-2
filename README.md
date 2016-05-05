# MINI-RETO-SEMANA-2
Playground para el mini reto correspondiente a la semana 2
import UIKit

//: Este es el Mini Reto de la semana 2

var numeros = 0 ... 100



for n in numeros {

        switch n {

                case 0 :
                    print ("numero cero")

                case 31 ... 39 :
                    print (n , "# Viva swift ")
            
    
        default :
            if  (n % 5) == 0 {
                        print (n ,"# Bingo!!!")
            }
            
        else if ( n % 2) == 0 {
                            print ( n ,"# Par" )
            }
                            else {
                                print ( n ,"# Impar")
                            }
                        }
}

