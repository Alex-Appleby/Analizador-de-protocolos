# Analizador de protocolos

Proyecto académico desarrollado en C para la materia Redes de Computadoras I. El programa recorre tramas incluidas en el código e interpreta sus encabezados según el protocolo identificado.

## Protocolos

- ARP
- IP
- ICMP
- TCP
- UDP

## Compilación y ejecución

Con GCC:

```bash
gcc Analizador_de_protocolos.c -o analizador
./analizador
```

## Alcance

Las tramas utilizadas para el análisis están declaradas dentro del archivo fuente. El proyecto no captura tráfico de red en tiempo real.
