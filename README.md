# Servidor y Cliente TCP en C++

## Descripción

Este proyecto contiene una implementación simple de un servidor y un cliente TCP utilizando C++. El objetivo es demostrar los conceptos básicos de la programación de sockets en C++ y proporcionar una base sobre la cual se puedan construir aplicaciones de red más complejas.


## Características

- **Servidor TCP**: Espera conexiones entrantes y envía un mensaje de saludo a los clientes.
- **Cliente TCP**: Se conecta al servidor y recibe el mensaje.

## Comenzando

### Prerequisitos

Para ejecutar estos programas, necesitarás:
- Un compilador de C++ (GCC recomendado)
- Sistema operativo compatible con sockets TCP (Linux, macOS, Windows con Cygwin/MinGW)

### Instalación

1. Clona el repositorio en tu máquina local:
  ```bash
  git clone [URL del repositorio]
  ```
2. Compilando el Servidor
  ```bash
     g++ -o servidor servidor.cpp
  ```
Esto creará un archivo ejecutable llamado servidor.
3. De manera similar, para compilar el cliente, ejecuta:

```bash
   g++ -o cliente cliente.cpp
```

Esto creará un archivo ejecutable llamado cliente.

## Ejecutando los Programas

Primero, ejecuta el servidor:

```bash 
./servidor
```

Luego, en una terminal diferente, ejecuta el cliente:

```bash 
./cliente
```
