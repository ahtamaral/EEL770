# EEL770 - Sistemas Operacionais
# UFRJ - 2021.1 - prof: Rodrigo Couto
# Autor: Artur Amaral | DRE: 119057968
# Descrição: Makefile.
# Obs: Este arquivo é inteiramente baseado no makefile exposto
# como exemplo no roteiro do trabalho.

CC = gcc
CFLAGS = -Wall
TARGET = disparador

all: $(TARGET)

$(TARGET): $(TARGET).c
	$(CC) $(CFLAGS) -o $(TARGET) $(TARGET).c

clean:
	$(RM) $(TARGET)

