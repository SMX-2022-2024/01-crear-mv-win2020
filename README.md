# 01-crear-mv-win2020

<!-- https://blogs.sap.com/2020/06/25/how-to-install-the-.net-framework-3.5-on-windows-server-2016-and-later/ -->

## Índex

**1.** [Definició de la màquina virtual](#1-definició-de-la-màquina-virtual)

**2.** [Configuració de les diferents opcions de la màquina virtual](#2-configuració-de-les-diferents-opcions-de-la-màquina-virtual)

1. [Instal·lació del sistema operatiu](./README.md#installació-del-sistema-operatiu)

1. [Inici de sessió (<kbd>CTRL</kbd> + <kbd>Supr</kbd>)](./README.md#inici-de-sessió-ctrl--supr)

1. [Desactivar que s'iniciï el **Server Manager** automàticament a l'inici de sessió](./README.md#desactivar-que-siniciï-el-server-manager-automàticament-a-linici-de-sessió)

1. [Desactivar que **```Windows Update```** descarregui automàticament els paquets a instal·lar.](./README.md#desactivar-que-windows-update-descarregui-automàticament-els-paquets-a-installar)

1. [Copiar la carpeta sources del *CD* a la carpeta **```c:\eines```**, per fer-lo servir quan instal·lem alguna de les *caracteristiques* de Windows.](./README.md#copiar-la-carpeta-sources-del-cd-a-la-carpeta-ceines-per-fer-lo-servir-quan-installem-alguna-de-les-caracteristiques-de-windows)

1. [Instal·lar la *caracteristica* de Windows **```.NET Framework 3.5```**](./README.md#installar-la-caracteristica-de-windows-net-framework-35)



## **1.** Definició de la màquina virtual

#### [torna a l'Índex](#índex)

Escull un **nom**, la carpeta per la **ubicació de la MV**, i: 

* **Type: ```Microsoft Windows```**

* **Version: ```Other Windows (64-bits)```**

![Alt text](./images/crear-mv-01-nom.png)

### Mida de la memòria RAM

A ser possible, és a dir, depenent del vostre portàtil, us recomano com a mínim una mica més de **```4 GB``` de RAM**.

* Selecciona **```4128 MB```** i 

* pressiona <kbd><u>N</u>ext</kbd> continuar.

![Alt text](./images/crear-mv-02-def-ram.png)

### Disc dur

#### Creació del *disc dur*

![Alt text](./images/crear-mv-03-def-hd.png)

* Selecciona <u>**```C```**</u>**```reate a virtual hard disk now```**, i

* pressiona <kbd>Create</kbd> per crear-lo ara.

#### Selecció del tipus de disc dur

![Alt text](./images/crear-mv-04-def-hd-type.png)

* Selecciona **```VDI (VirtualBox Disk Image)```** i

* pressiona <kbd><u>N</u>ext</kbd> continuar.

#### Emmagatzematge al disc dur físic

![Alt text](./images/crear-mv-05-def-hd-allocated.png)

* Selecciona **```Dynamically allocated```** (***Assignat dinàmicament***) i

* pressiona <kbd><u>N</u>ext</kbd> continuar.

#### Ubicació i mida del fitxer

* **Mida**: **```100 GB```** 

![Alt text](./images/crear-mv-06-def-hd-location-size.png)

* Selecciona **```100 GB```** i

* pressiona <kbd><u>C</u>reate</kbd> per crear el disc dur.

## **2.**  Configuració de les diferents opcions de la màquina virtual

#### [torna a l'Índex](#índex)

Un cop ja tenim creada la **definició** i el **disc dur** de la màquina virtual, procedirem a modificar diferents detalls de la configuració.

![Alt text](./images/crear-mv-07-detalls.png)

#### Interfícies de xarxa

Per defecte una màquina virtual té només una interfície de xarxa i la té configurada com a **```NAT```**.

![Alt text](./images/crear-mv-08-adptador1.png)

Si passem a la pestanya del **segon adaptador de xarxa**.

![Alt text](./images/crear-mv-09-adptador2.png)

* Seleccionem **```Host-only Adapter```** i

* passem a la pestanya del **tercer adaptador de xarxa**.

![Alt text](./images/image-12.png)

![Alt text](./images/image-13.png)

![Alt text](./images/image-14.png)

![Alt text](./images/image-15.png)

## Instal·lació del sistema operatiu

![Alt text](./images/image-16.png)

![Alt text](./images/image-17.png)

![Alt text](./images/image-19.png)

![Alt text](./images/image-20.png)

![Alt text](./images/image-21.png)

![Alt text](./images/image-22.png)

![Alt text](./images/image-23.png)

## Inici de sessió (<kbd>CTRL</kbd> + <kbd>Supr</kbd>)

![Alt text](./images/image-24.png)


Marcar "***Don't show this message again***"

![Alt text](./images/image-25.png)

![Alt text](./images/image-26.png)

## Desactivar que s'iniciï el **Server Manager** automàticament a l'inici de sessió

![Alt text](./images/image-27.png)

![Alt text](./images/image-28.png)

## Desactivar que **```Windows Update```** descarregui automàticament els paquets a instal·lar.

![Alt text](./images/image-29.png)

![Alt text](./images/image-30.png)

![Alt text](./images/image-31.png)

![Alt text](./images/image-32.png)

![Alt text](./images/image-34.png)

## Copiar la carpeta sources del *CD* a la carpeta **```c:\eines```**, per fer-lo servir quan instal·lem alguna de les *caracteristiques* de Windows.

![Alt text](./images/image-35.png)

![Alt text](./images/image-37.png)

![Alt text](./images/image-38.png)


![Alt text](./images/image-36.png)

![Alt text](./images/image-39.png)

![Alt text](./images/image-40.png)

![Alt text](./images/image-41.png)

## Instal·lar la *caracteristica* de Windows **```.NET Framework 3.5```**

![Alt text](./images/image-42.png)


![Alt text](./images/image-43.png)

![Alt text](./images/image-44.png)

![Alt text](./images/image-45.png)

![Alt text](./images/image-46.png)

![Alt text](./images/image-48.png)

![Alt text](./images/image-49.png)

![Alt text](./images/image-50.png)

![Alt text](./images/image-52.png)

![Alt text](./images/image-53.png)

![Alt text](./images/image-54.png)

![Alt text](./images/image-55.png)


![Alt text](./images/image-57.png)

![Alt text](./images/image-58.png)

![Alt text](./images/image-59.png)

<!-- 

![Alt text](./images/image-60.png)

![Alt text](./images/image-61.png)

![Alt text](./images/image-62.png)

-->

Snapshoot


![Alt text](./images/image-64.png)

![Alt text](./images/image-65.png)

![Alt text](./images/image-67.png)

![Alt text](./images/image-68.png)

![Alt text](./images/image-69.png)

![Alt text](./images/image-71.png)
