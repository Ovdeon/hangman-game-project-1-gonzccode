# Project

Hello new developers; Now is the time to start working on your project.
Hangman game! is the name of the project; If you want to know how to play this game, check the link below.

https://www.youtube.com/watch?v=leW9ZotUVYo

## Instructions
- Read all the bank of words or phrases from the JSON file. Select one and start the game.
- You will always receive numbers and letters, not symbols(except blank characters)
- Use everything you have learned so far, and try new things. Not include classes.
- Try to create the best user experience in your terminal.

## Bonus
- write tests.

## Installation
1. Download the project from github
2. Install python 3.11.1
3. Create a virtual environment
4. Active the environment
5. Run the game with this command: 
```python
python main.py
```

### What was your creative process:
1. Investigué acerca del juego para entender de qué trata.
2. Escribí en un borrador el flujo de todo el juego, desde escoger la palabra hasta saber si el jugador perdió o ganó.
3. Identifiqué las funciones que tendría por cada acción del juego.
4. Fui armando en orden las funciones que necesitaba, iniciando por load_data() hasta hangman_game().
5. Dentro de cada función coloqué las variables con el nombre que describa el valor que contendrá y todos los pasos relacionados a la función.
6. En cada paso realicé pruebas con ayuda del print para saber que es lo que obtenía.
7. Agregué más palabras al archivo json para hacer pruebas con distintos casos.
8. Una vez que obtuve gran parte del flujo del juego, coloqué condicionales para obtener un resultado en casos se ingrese o coloque otras opciones.
9. Armé la vista inicial de bienvenida y el bucle para preguntar si se desea jugar o no.
10. Por último realicé pruebas al flujo total del juego para ver si surgía un error.