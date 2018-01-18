#  Makefile 
#  Auteur : Fadil TCHAKPIDE 
#  Email  : fadilt@free.fr 
#  Date   : 18/01/2018


# définition des commandes utilisées
CC = gcc
ECHO = echo
RM = rm -f
TAR = tar
MKDIR = mkdir
CHMOD = chmod
CP = rsync -R
# déclaration des options du compilateur
CFLAGS = -Wall 
LDFLAGS = -lpthread -lm

# définition des fichiers et dossiers
PROGNAME = mutex_trains

SOURCES = partie_1.c 
OBJ = $(SOURCES:.c=.o)



all: $(PROGNAME)

$(PROGNAME): $(OBJ)
	$(CC) $(OBJ) $(LDFLAGS) $(CFLAGS) -o $(PROGNAME)