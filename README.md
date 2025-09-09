# 🏦 Bank Project – Java + Maven  

Este proyecto es una **simulación de sistema bancario** desarrollado en **Java 17** y gestionado con **Maven**.  

## 📂 Estructura principal  
```
src/
 └── main/
     ├── java/com/logicasp
     │   ├── exception/        # Manejo de excepciones personalizadas
     │   ├── model/            # Clases del modelo de datos
     │   ├── repository/       # Persistencia en archivos JSON
     │   ├── service/          
     │   │   ├── strategies/   # Estrategias de cálculo de intereses
     │   │   └── BankService   # Lógica principal del sistema bancario
     │   └── util/             # Utilidades (ej. manejo de JSON)
     │
     ├── resources/            # Archivos de datos en JSON
     │   ├── accounts.json
     │   ├── customers.json
     │   └── transactions.json
     │
     └── Main.java             # Punto de entrada de la aplicación
```

## ⚙️ Características  
- Registro y administración de **clientes** y **cuentas bancarias**.  
- Gestión de **transacciones**.  
- Cálculo de **intereses** mediante diferentes estrategias (`SimpleRate`, `TieredRate`, etc).  
- Persistencia en archivos **JSON**.  

## 🛠️ Tecnologías  
- **Java 17**  
- **Maven**  
- **JSON** para persistencia de datos  

## 🚀 Ejecución  
1. Clonar el repositorio  
   ```bash
   git clone https://github.com/tu-usuario/bank.git
   cd bank
   ```
2. Compilar y ejecutar con Maven  
   ```bash
   mvn clean install
   mvn exec:java -Dexec.mainClass="com.logicasp.Main"
   ```

---

✍️ Autor: *[Tu Nombre]*  
