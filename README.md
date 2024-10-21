# Dioptre-to-Millimetre-Calculator-or-Calculadora-de-Dioptr-as-a-Mil-metros
 A dioptre-to-millimetre calculator, in a simple hashtag#Python function. This calculation helps determine the curvature of the cornea when performing contact lens fittings. Here’s an example of it.


#1) Dioptria a milimetro / Diopter to millimeter

milimetro = (0.3376 / 43.00) * 1000 # Para obtener el resultado en milimetro debemos tomar la medida en dioptria dividiendola por 0.3376 y luego multiplicarlo por 1000 (0.3376 es una constante de la diferencia del indice de refracción de la cornea y el aire)
                                    # To obtain the result in millimeters we must take the measurement in diopter by dividing it by 0.3376 and then multiplying it by 1000 (0.3376 is a constant of the difference in the refractive index of the cornea and the air)

#2)  Milimetro a dioptria / Millimeter to diopter

dioptria = (0.3376 / 8.4) * 1000 # Para obtener el resultado en dioptria debemos tomar la medida en milimetro dividiendola por 0.3376 y luego multiplicarlo por 1000 (0.3376 es una constante de la diferencia del indice de refracción de la cornea y el aire)
                                 # To obtain the result in diopter we must take the measurement in millimeters by dividing it by 0.3376 and then multiplying it by 1000 (0.3376 is a constant of the difference in the refractive index of the cornea and the air)

milimetro_final = round(milimetro, 2)
dioptria_final = round(dioptria, 2)

print(milimetro_final)
print(dioptria_final)
7.85
40.19
