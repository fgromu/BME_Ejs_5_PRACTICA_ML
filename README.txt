Iteración 1: Ej_5_1_01.ipynb
1.1. Documentos necesarios
ejemplos_doble_suelo.csv
OHLC_pck_Ej_5_1/{i}_OHLC.pkl
PDFs_Graficas_con_etq_Ej_5_1/{nombre}
Graficas_Ej_5_1_Todas.pdf
df_maestro_Ej_5_1.csv


a) Generación de etiquetas
A partir de iteración 17, el programa empieza a fallar por el tema de la representación en el notebook.
Asi que como quiero crear 150 etiquetas, pues repito el programa 10 veces la generación de 15 etiquetas y cruzo los dedos para que no coincidan días de comienzo de generar la gráfica.

1.2 Comentarios necesarios:
1.2.a: Extraer datos del ibex (sin dividendos) desde 2000-01-03 hasta 2019-06-10
A partir de iteración 17, el programa empieza a fallar por el tema de la representación en el notebook. Asi que como quiero crear 150 etiquetas, pues repito el programa 10 veces la generación de 15 etiquetas.
Después de varias pruebas, he visto que mejor hacerlo con ventanas de 50

Iteración 2: Ej_5_2_01.ipynb
2.1. Documentos necesarios
ejemplos_doble_suelo_doble_techo.csv
df_maestro_Ej_5_2.csv
OHLC_pck_Ej_5_2/{i}_OHLC_Ej5_2.pkl
PDFs_Graficas_con_etq_Ej_5_2/{i}
Graficas_Ej_5_2_Todas.pdf
ejemplos_doble_suelo_doble_techo_test_nuevo_Ej3_3.csv herrata, mejor haberlo llamado Ej2_3
OHLC_pck_Ej_5_2_punto3_new_test/{i}_OHLC_Ej5_2_punto3_new_test.pkl
df_data_eu-stoxx50.csv
df_maestro_Ej_5_2_punto3_new_test.csv
Datos históricos Euro Stoxx 50.csv
Carpeta_graficas_predichas_eurostock50

2.2 Comentarios necesarios:
2.2.a: Extraer datos del ibex (sin dividendos) desde 2000-01-03 hasta 2019-06-10
A partir de iteración 17, el programa empieza a fallar por el tema de la representación en el notebook. Así que como quiero crear 150 etiquetas, pues repito el programa 10 veces la generación de 15 etiquetas.
Después de varias pruebas, he visto que mejor hacerlo con ventanas de 50
2.2.B: # 3.8.1 knn predice con respecto a la información en df_maestro peor que el dtree
# porque solo predice 'no'. Así que lo hago con respecto al algoritmo dTree,
# que me predice algunos doble suelos y doble techos.



Iteración 3: Ej_5_3_00.ipynb
3.1. Documentos necesarios
ejemplos_doble_suelo_doble_techo.csv
df_maestro_Ej_5_3.csv
ejemplos_doble_suelo_doble_techo_test_nuevo_Ej3_S.csv
df_maestro_Ej_5_3_S.csv
ejemplos_doble_suelo_doble_techo_test_nuevo_Ej3_S2.csv
df_maestro_Ej_5_3_S2.csv
ejemplos_doble_suelo_doble_techo_test_nuevo_Ej3_S3.csv
df_maestro_Ej_5_3_S3.csv
../data/benchmark_data.pkl
OHLC_pck_Ej_5_2/{i}_OHLC_Ej5_2.pkl
OHLC_pck_Ej_5_3_S/{i}_OHLC_Ej5_3_S.pkl
OHLC_pck_Ej_5_3_S/{i}_OHLC_Ej5_3_S.pkl
OHLC_pck_Ej_5_3_S2/{i}_OHLC_Ej5_3_S2.pkl
OHLC_pck_Ej_5_3_S3/{i}_OHLC_Ej5_3_S3.pkl
df_maestro_Ej_5_3_3_iteracion_0.csv
df_maestro_Ej_5_3_3_iteracion_1.csv
df_maestro_Ej_5_3_3_iteracion_2.csv
df_maestro_Ej_5_3_3_iteracion_3.csv

3.2 Comentarios necesarios:
3.2.a: Extraer datos del ibex (sin dividendos) desde 2000-01-03 hasta 2019-06-10
A partir de iteración 17, el programa empieza a fallar por el tema de la representación en el notebook. Así que como quiero crear 150 etiquetas, pues repito el programa 10 veces la generación de 15 etiquetas.
Después de varias pruebas, he visto que mejor hacerlo con ventanas de 50

He dejado una libreria que me he creado para el TFM (semiterminada) sobre la parte de ML: : Ej_5_lib_fer.ipynb