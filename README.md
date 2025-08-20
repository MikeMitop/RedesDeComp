# Redes de Computación, Taller #1


## Resultado y explicación del ejemplo `first` (ns-3)

### Al ejecutar/¿Cómo ejecutar?:

```bash
./ns3 run first
```

## Se obtuvo lo siguiente:

```pgsql
At time +2s       client sent 1024 bytes to 10.1.1.2 port 9
At time +2.00369s server received 1024 bytes from 10.1.1.1 port 49153
At time +2.00369s server sent 1024 bytes to 10.1.1.1 port 49153
At time +2.00737s client received 1024 bytes from 10.1.1.2 port 9
```

## Análisis:

**Con el resultado dado, se puede deducir que:**

* A los **+2.00000 segundos** el cliente envía un paquete de **1024 Bytes** al servidor **(10.1.1.2:9)**.

* A los **+2.00369 segundos** el servidor lo recibe y, en ese mismo instante, **envía el eco** de vuelta.

* A los **+2.00737 segundos** el cliente **recibe el eco.**

## Tiempos:

* Ida: **~3.69 ms**

* Vuelta: **~3.68 ms**

* RTT (ida y vuelta): **~7.37 ms**


