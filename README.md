# SoC_initial

1. instalar litex https://github.com/enjoy-digital/litex
2. Descargar el paquete WP04
3. ejecutar "python3 buildSoCproject.py"
4. jtgcfg prog -d NexysA7 -i 0 -f ./build/nexys4ddr/gateware/nexys4ddr.bit
5. ir a la carpeta  firmware
6. ejecutar "make all"
7. salir de la carpeta firmware  
8. ejecutar litex_term.py /dev/ttyUSB1 --kernel firmware/firmware.bin
9.  enteder el programa que esta  ejecutando el procesardor 

