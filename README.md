# CALCULADORA DE RESISTENCIA - ELECTRÓNICA
App para escritorio desarrollada en python, puede calcular el valor de la resistencia de 3,4,5 y 6 bandas con resultado en ohmios (Ω)

Recuerda:

- Para las resistencias de 3 bandas se deshabilita la tolerancia ya que todos tienen una tolerancia predeterminada del 20%

- CAMPO TCR: El coeficiente de temperatura de resistencia (TCR) es el cálculo de un cambio relativo de resistencia por grado de cambio de temperatura. Se mide en ppm/°C (1 ppm = 0,0001 %).

- VARIACIÓN DE TEMPERATURA: La entrada de datos para este valor solo se habilita para resistencias de 6 bandas

- EN EL CAMPO TEMPERATURA INGRESAR EL INCREMENTO O DECREMENTO DE LA TEMPERATURA TENIENDO EN CUENTA  25°C PARA LA TEMPERATURA AMBIENTE
- EJEMPLO DE RESULTADO:

 ==================================================

            NÚMERO DE BANDAS : 6                    # LA RESISTENCIA TIENE 3 BANDAS
            VALORES DE BANDAS: 105                  # DIGITOS DE LAS BANDAS
              TOLERANCIA +/- : 0.105 Ω              # TOLERANCIA EN OHMIOS
           V. NOMINAL MÁXIMO : 10.605 Ω             # VALOR NOMINAL MÁXIMO QUE PUEDE TENER LA RESISTENCIA A TEMP. AMBIENTE
               VALOR NOMINAL : 10.5 Ω               # VALOR NOMINAL
           V. NOMINAL MÍNIMO : 10.395 Ω             # VALOR NOMINAL MINÍMO QUE PUEDE TENER LA RESISTENCIA A TEMP, AMBIENTE
          ------------------------------
                 TEMPERATURA : +10°C                # + O -  AL INGRESAR EL DATO INDICAMOS SI LA TEMPERATURA AUMENTA O DISMINUYE
    TOLERANCIA CON Temp.  +/-: 0.0105 Ω             # TOLERANCIA + o - CON RESULTADO EN OHMIOS 
     VALOR NOMINAL CON Temp. : 10.5105 Ω            # VALOR NOMINAL SI LA TEMPERATURA AUMENTA EN +10°C
    % DE VARIACIÓN CON Temp.  +/-: 0.1%             # PORCENTAJE DE VARIACIÓN CON X °c TEMPERATURA
==================================================
         
