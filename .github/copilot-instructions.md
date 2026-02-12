'''Aqui le damos instrucciones a la IA para que sepa como debe comportarse a la hora de generar codigo para el proyecto de forecasting de ventas. Estas instrucciones se aplicaran a todos los archivos del proyecto, ya que el valor de applyTo es **, lo que significa que se aplican a todos los archivos del proyecto. Las instrucciones son las siguientes:'''

* empieza siempre tu respuesta con el emoji 🤖
* responde siempre en español
* recuerda que las variables del dataframe df que tienes que usar siempre en el codigo que generes son:
df:['fecha', 'producto_id', 'nombre', 'categoria', 'subcategoria',
       'precio_base', 'es_estrella', 'unidades_vendidas', 'precio_venta',
       'ingresos',
       ...
       'subcategoria_h_Esterilla Yoga', 'subcategoria_h_Mancuernas Ajustables',
       'subcategoria_h_Mochila Trekking', 'subcategoria_h_Pesa Rusa',
       'subcategoria_h_Pesas Casa', 'subcategoria_h_Rodillera Yoga',
       'subcategoria_h_Ropa Montaña', 'subcategoria_h_Ropa Running',
       'subcategoria_h_Zapatillas Running', 'subcategoria_h_Zapatillas Trail'
competencia_df: ['fecha', 'producto_id', 'Amazon', 'Decathlon', 'Deporvillage']
* no uses en tu codigo ninguna otra variable que no este en la lista anterior salvo que la hayas definido tu mismo en el codigo que generes
* no uses ninguna libreria que no sean estas: pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter, streamlit, holidays
