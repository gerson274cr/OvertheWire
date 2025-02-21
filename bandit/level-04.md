## 📖 Plantilla para Niveles

# Wargame - Nivel 04

## 🔍 Descripción del reto
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

## 🛠️ Comandos utilizados
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
file inhere/*
cat inhere/-file07
```

## 🎯 Solución paso a paso


## 🔑 Credenciales para el siguiente nivel
**Usuario:** bandit5
**Contraseña:**  4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw 

## 📝 Notas y aprendizaje
Filtrar el archivo que no está encriptado
Podemos identificar el archivo no encriptado revisando su tipo con file:

```bash
file inhere/*
Esto mostrará una lista con los tipos de archivos. Buscamos el que sea ASCII text (texto sin cifrar). Ejemplo de salida:
```

```bash
inhere/-file00: data
inhere/-file01: data
inhere/-file02: ASCII text
inhere/-file03: data
```

En este caso, el archivo no encriptado es inhere/-file02.
