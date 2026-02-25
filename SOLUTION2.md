# Welcome to Codespace
## Imprime texto en la terminal
echo "Hola Mundo"

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
