# Define el nombre del ejecutable
NAME = Ejecutable
COMPILER = cc
# Define las flags del compilador
CFLAGS = -Wall -Wextra -Werror
# Lista de archivos fuente del proyecto
SOURCES = src/main.c src/utils.c
# Regla principal que compila el programa
all: $(NAME)
	$(NAME):
	$(COMPILER) $(CFLAGS) $(SOURCES) -o $(NAME)
# Elimina el archivo ejecutable
delete:
	rm  -f $(NAME)
# Ejecuta clean y luego all para recompilar todo
re: 
	rm clean all
# Ejecuta el programa
run: $(NAME)
	./$(NAME)
# Declara las reglas que no generan archivos
.PHONY: all delete re run
