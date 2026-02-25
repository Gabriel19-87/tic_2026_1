# Welcome to Codespace
## Imprime texto en la terminal
echo "Hola Mundo"

## Imprime texto con formato
printf "Esto es %s con %d formato\n" "un ejemplo" 1

## Animación en la Terminal
#!/bin/bash

frames=("(^-^)" "(>_<)" "(^-^)")
clear
while true; do
  for frame in "${frames[@]}"; do
    echo "$frame"
    sleep 0.5
    clear
  done
done

# figlet y toilet:
## Instalar si no están instalados
sudo apt install figlet toilet

## Generar texto artístico
figlet "Ubuntu"
toilet -f mono12 -F gay "Terminal Art"

## Haz un dibujo

echo "  /\\_/\\"
echo " ( o.o )"
echo "  > ^ <"

