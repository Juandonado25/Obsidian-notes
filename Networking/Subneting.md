Dividir una red en varias redes. 

1. primero hay que evaluar que clase de ip va a satisfacer la cantidad de dispositivos finales que se va a direccionar. en el caso de que son 500 dispositivos tiene que ser una ip de clase B que puede direccionar 2⁽16) maquinas. mas que suficiente

2. una vez que sabemos cual vamos a utilizar, tenemos que calcular cuantos bits se le van a pedir prestados a la mascara para satisfacer la cantidad de areas, la formula para calcularlo es 2^n >=Areas. En el caso de que hayan 5 areas la formula va a ser s³=8, dado a que 8 > 5, por lo cual 3 son los bits minimos para poder direccionar las 5 areas, por lo tanto la nueva mascara de subred tiene 3 bits mas en 1 osea que seria una mascara de /19.


Una vez haga los calculos anterioes puedo armar el **Detalle de la red** , este informe que tiene que llevar por cada area:
- ip de red
- 1era ip util
- ultima ip util
- ip broadcast
- cantdad de pc por red