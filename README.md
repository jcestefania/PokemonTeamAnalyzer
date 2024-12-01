# PokemonTeamAnalyzer

## Descripción
PokemonTeamAnalyzer es una herramienta que ayuda a Ash Ketchum a decidir cuál de sus dos equipos de Pokémon tiene una mejor ventaja estratégica para enfrentarse a un líder de gimnasio especializado en Pokémon de tipo planta. El análisis se basa en las estadísticas de ataque y los tipos de los Pokémon, utilizando datos obtenidos de la API pública de Pokémon.

## Equipos
- **Equipo 1:** Charizard, Dragonair, Seadra, Pidgeot, Kadabra, Butterfree
- **Equipo 2:** Feraligatr, Snorlax, Gyarados, Fearow, Zapdos, Hypno

## Funcionalidades
1. **Consulta a la API pública de Pokémon** para obtener las estadísticas base de cada Pokémon.
2. Calcular las ventajas y desventajas de tipo basadas en el gimnasio de tipo planta:
   - Ventaja de tipo: Multiplicador de **1.5**.
   - Desventaja de tipo: Multiplicador de **0.5**.
   - Sin ventaja/desventaja: Multiplicador de **1**.
3. Evaluar los equipos en base a las siguientes estadísticas:
   - **Ataque Especial** (`special-attack`).
   - **Defensa Especial** (`special-defense`).
4. Identificar el Pokémon más débil de cada equipo y sugerir reemplazos.
5. Representar gráficamente los resultados.

## Requisitos
- Python 3.x
- Librerías: `requests`, `pandas`, `matplotlib`

## Uso
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/PokemonTeamAnalyzer.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd PokemonTeamAnalyzer
   ```

3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

4. Ejecuta el notebook `pokemonTeamAnalyzer.ipynb` para realizar el análisis.
  
