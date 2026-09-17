# ETL Microsoft Fabric

## Descripción

Proyecto de integración y transformación de datos desarrollado en Microsoft Fabric, utilizando una arquitectura de datos por capas para realizar procesos de ingestión, transformación, limpieza y almacenamiento.

El proyecto integra diferentes componentes de Microsoft Fabric para construir un flujo ETL desde la ingesta de datos hasta su preparación para el análisis.

## Arquitectura

El proceso sigue una arquitectura por capas:

**Fuente de datos → Bronze → Silver → Gold → Análisis**

### Bronze

En esta capa se realiza la ingesta inicial de los datos, conservando los datos provenientes de las fuentes de origen.

### Silver

En esta etapa se realizan procesos de limpieza, transformación y preparación de los datos para mejorar su calidad y estructura.

### Gold

En esta capa se preparan los datos transformados para su utilización en procesos analíticos y de negocio.

## Tecnologías utilizadas

* Microsoft Fabric
* Data Pipelines
* Copy Jobs
* Lakehouse
* Dataflows Gen2
* Notebooks
* SQL Analytics Endpoint
* Arquitectura Medallion
* Procesos ETL

## Componentes del proyecto

El workspace utilizado para desarrollar el proyecto contiene diferentes componentes:

* Copy Jobs
* Pipelines
* Dataflows Gen2
* Notebooks
* Lakehouse
* SQL Analytics Endpoint
* Activator

## Principales procesos

Entre los procesos desarrollados se encuentran:

* Ingesta de datos
* Movimiento de datos entre capas
* Limpieza y transformación
* Preprocesamiento
* Creación y preparación de tablas
* Procesamiento de datos hacia la capa Gold
* Orquestación de procesos mediante pipelines

## Objetivo

El objetivo del proyecto es demostrar el desarrollo de un proceso ETL utilizando Microsoft Fabric, integrando diferentes herramientas de ingeniería de datos para mover, transformar y preparar información para análisis posteriores.

## Evidencias

Este repositorio contiene capturas y documentación del proceso desarrollado en Microsoft Fabric.

## Herramientas

**Microsoft Fabric | Lakehouse | Pipelines | Dataflows Gen2 | Notebooks | SQL Analytics Endpoint**

