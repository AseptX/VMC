# VMC
Projet VMC

La tension de sortie du capteur (Vrh) est donné par la relation : ((Rh + 12.5) * 5) / 125. Rh étant le taux d'humidité dans l'air en % compris entre 0% et 100%

Pour une humidité de 50% on a Vrh = 2.5V. Pour 100% on a 4.5V et pour 0% on a 500 mV. 

Peu importe la valeur de e (tension arrivant sur la borne positif de l'hystéresis) la différence entre Vh et Vl est de 5y (y est le rapport R1/R2, R1 étant la resistance en entrée de l'AOP)

La valeur de e détermine l'offset des bornes de l'hystéresis. 

Ici sera utilisé 5% d'humidité entre les bornes de l'hystéresis soit un rapport y de 0.04.
Le potentiomètre permettera de régler la tension e entre 1.3V (20%) et 2.5V (50%). 

Quand le potentiomèrre sera à 0 Ohm, la resistance serie de 2.7K permettera d'avoir un rapport de pont diviseur de 0.26 => 2700/ (2700+7700) soit 1.3V. 
Quand le potentimètre sera en buté de 5K, la resistance total sera de 7700 et on aura donc un rapport de 0.5 soit 2.5V. 
