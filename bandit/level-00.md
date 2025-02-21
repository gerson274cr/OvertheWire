## 📖 Plantilla para Niveles

# Wargame - Nivel 00

## 🔍 Descripción del reto

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.


## 🛠️ Comandos utilizados
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls -la
cat readme
```

## 🎯 Solución paso a paso

## 🔑 Credenciales para el siguiente nivel
**Usuario:XXX
**Contraseña: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If  

## 📝 Notas y aprendizaje
https://en.wikipedia.org/wiki/Secure_Shell
https://www.wikihow.com/Use-SSH
```
