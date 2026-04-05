import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# 1. Cargar datos (Simulación de estructura INE)
# En un caso real usarías: df = pd.read_csv('esi_2024.csv')
data = {
    'Genero': ['Masculino', 'Femenino'] * 50,
    'Sector': ['Minería', 'Servicios', 'Tecnología', 'Comercio', 'Agricultura'] * 20,
    'Ingreso_Mensual': [1200000, 950000, 1500000, 800000, 600000] * 20 # Valores base
}
df = pd.DataFrame(data)

# 2. Cálculo de la Brecha Salarial Promedio
ingreso_promedio = df.groupby('Genero')['Ingreso_Mensual'].mean()
brecha = (1 - (ingreso_promedio['Femenino'] / ingreso_promedio['Masculino'])) * 100

print(f"Ingreso Promedio Hombres: ${ingreso_promedio['Masculino']:,.0f}")
print(f"Ingreso Promedio Mujeres: ${ingreso_promedio['Femenino']:,.0f}")
print(f"Brecha Salarial Calculada: {brecha:.2f}%")

# 3. Visualización Profesional para el README
plt.figure(figsize=(10, 6))
sns.barplot(x='Genero', y='Ingreso_Mensual', data=df, palette='viridis')
plt.title('Comparación de Ingresos Mensuales por Género en Chile')
plt.ylabel('Ingreso Promedio (CLP)')
plt.show()
