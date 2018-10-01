# Ejercicios tema 1

## Ejercicios 1.
### Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar [este artículo en infoautónomos sobre el tema](https://infoautonomos.eleconomista.es/consultas-a-la-comunidad/988/).

Ordenador tipo servidor utilizado
El ordenador tipo servidor que hemos utilizado es ***HP ProLiant ML350 Gen9 Intel Xeon E5-2603V4/8GB***.

Descripción [PC componentes](https://www.pccomponentes.com/hp-proliant-ml350-gen9-intel-xeon-e5-2603v4-8gb)

El servidor ML350 Gen9 aprovecha los procesadores Intel &reg Xeon &reg E5-2600 v3 y v4 con hasta un 21 % de aumento del rendimiento, además de las más reciente HPE DDR4 SmartMemory, ofreciendo un aumento del rendimiento de hasta el 23 % Soporte adicional para SAS de 12 Gb/s, NIC de 4x1 GbE integrado ocn una amplia gama de opciones de gráficos y computación. Gestione su servidor HPE ProLiant en cualquier entorno de TI mediante la automatización de las tareas de administración del ciclo de vida del servidor más esenciales: implementar, actualizar, supervisar y mantener con facilidad. El servidor ML350 Gen9 es ideal para la infraestructura de TI empresarial para aplicaciones de misión crítica.

Especificaciones HP ProLiant ML350 Gen9
**Procesador**
Frecuencia del procesador: 1,7 GHz ,familia de procesador: Intel Xeon E5 v4
,memoria interna máxima que admite el procesador: 1536 GB,tipos de memoria que admite el procesador: DDR4-SDRAM,Velocidad de reloj de memoria que admite el procesador: 1600,1866 MHz
ancho de banda de memoria soportada por el procesador (max): 59,7 GB/s.

**Memoria**
Memoria interna: 8 GB,Tipo de memoria interna: DDR4-SDRAM.
Memoria interna máxima: 768 GB,Ranuras de memoria: 24 DIMM.
Velocidad de memoria del reloj: 2400 MHz.

**Precio: 1729€**

**Amortización a 4 años**
- El cálculo de la amortización es: 1729/4 = 432,25€.
- Por tanto la amortización a 4 años es de 432.25€.

**Amortización a 7 años**
- El cálculo de la amortización es 1729/7 = 247€.
- Por tanto la amortización a 7 años es de 247€.

## Ejercicios 2.
Usando las tablas de precios de servicios de alojamiento en Internet "clásicos", es decir que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

### Configuración Vitual Private Servers [dinahosting](https://dinahosting.com/vps/configurador/modelo-1)
Hemos escogido para el Virtual Private Servers la empresa dinahosting y hemos escogido esta configuración que mostramos en la siguiente imagen.
El coste mensual es de ***162€***

![Vps](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/vps.png?raw=true "Vps")

**Para el caso de que la infraestructura se usa sólo el 1%**
- 162€ x 12 meses x 0.01 = 19.44€/año

**Para el caso de que la infraestructura se usa sólo el 10%**
- 162€ x 12 meses x 0.1 = 194.4€/año

Hemos escogido el proveedor de servidcios en la nube [acens](https://www.acens.com/cloud/cloud-servers/)
y hemos escogido esta configuración que aparece en la imagen, la configuración es ***One Cloud L***
El coste mensual es de ***59.90€***

![Cloud](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/cloud.png "Cloud")

**Para el caso de que la infraestructura se usa sólo el 1%**
- 59.90€ x 12 meses x 0.01 = 7.188 €/año

**Para el caso de que la infraestructura se usa sólo el 10%**
- 59.90€ x 12 meses x 0.1 = 71.88 €/año

## Ejercicios 3.
En general, cualquier ordenador con menos de 5 o 6 años tendrás estos flags. ¿Qué modelo de procesor es? ¿Qué aparece como salida de esa orden? si usas una máquina virtual, ¿qué resultado da? ¿Y una Raspberry Pi o, si tienes acceso, el procesador del móvil?

**Procesador portátil**: ***Intel(R) Core(TM) i7-3740QM CPU @ 2.70GHZ***

Para obtener la información del MacBook pro hago uso del siguiente comando :
***sysctl -n machdep.cpu.brand_string***

Dado que utilizo una máquina virtual de Ubuntu la salida que me aparece es vacío, está desactivado.
![salida](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/egrep.png?raw=true "salida")
## Ejercicios 4.
1. Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok. Alternativamente(o además), usar lscpu como se indica arriba.

- Salida del comando kvm-ok, después de su instalación.

![kvm-ok](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/kvm-ok.png)

- Salida de lscpu.

![lscpu](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/lscpu.png?raw=true "lscpu")

2. Instalar un hivervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.

La instalación de hivervisor para gestionar máquinas virtuales es VirtualBox
![virtualbox](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/virtualBox.png?raw=true "virtualBox")

## Ejercicios 5.
1. Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.

Actualmente tengo una cuenta de azure que abrí hace tiempo y tengo algunos ejemplos como podemos ver en la imagen.

![azure](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/azure.png?raw=true "azure")

## Ejercicios 6.
1. Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube anteriores.

Usamos OpenStack y nos registramos en la plataforma, en la siguiente imagen podemos ver mi perfil en OpenStack.
![openStack](https://github.com/juaneml/Ejercicios-IV/blob/master/tema1/imagenes/openStack.png?raw=true "openStack")
