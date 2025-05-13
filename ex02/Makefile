# Define el nombre del ejecutable
NAME = Ejecutable
# Define el compilador a utilizar
CC = cc
# Define las flags del compilador
CFLAGS = -Wall -Wextra -Werror
# Define el comando para eliminar archivos
RM = rm -rf
# Define la ubicación de las librerías
LIB_FOLDER = inc
# Define la ubicación de la librería printf
LIB_PRINTF_FOLDER = ./$(LIB_FOLDER/printf
# Define el archivo de la librería printf
LIB_PRINTF = $(LIB_PRINTF_FOLDER)/libprintf.a
# Define el comando para llamar al Makefile de printf
LIBFT_MAKEFILE = make -C $(LIB_PRINTF_FOLDER)
# Define los includes para la compilación
INCLUDES = -I$(LIB_PRINTF_FOLDER)
# Define la ruta a las librerías
LIBPATH = -L$(LIB_PRINTF_FOLDER)
# Define las librerías a enlazar
LIBS = -lftprintf
# Define la carpeta donde están los archivos fuente
SRC_FOLDER = src/
# Lista los archivos fuente
SRC_FILES = main.c \
# Concatena la ruta con los nombres de archivos
SRCS = $(addprefix $(SRC_FODLER), $(SRC_FILES))
# Genera los nombres de los archivos objeto
OBJ_FILES = $(SRCS: .c=.o)
# -- RULES -- #
# Regla principal que compila el programa y la librería printf
all: $(NAME) printf-all
# Regla patrón para compilar cada archivo .c a .o
 %.o: %.c
 $(COMPILER) $(FLAGS) -c $< -o $@
# Enlaza los objetos con la librería para crear el ejecutable
$(NAME): $(OBJ_FILES) $(LIB_PRINTF)
	$(COMPILER) $(FLAGS) $(INCLUDE) $(LIBPATH) $^ $(LIBS) 
# Elimina los archivos objeto y limpia printf
clean: printf-clean
	$(RM) $(OBJ_FILES)
# Limpieza completa: elimina objetos y ejecutable
fclean: printf-fclean clean
	$(RM) $(NAME)
# Recompila todo desde cero
re: printf-re clean all
# Declara reglas que no generan archivos
run:
# -- UTILS -- #
# Ejecuta el programa
run:
	
# -- LIBRARIES -- #

# Compila la librería printf

# Recompila la librería printf

# Limpia los objetos de printf

# Limpia completamente printf
