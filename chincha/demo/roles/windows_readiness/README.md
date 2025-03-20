Readiness: Configuracion Centralizada
======================================

## Descripcion del caso de uso

*Esta automatización permite realizar un Readiness/validación del servicio de IIS y los application Pools de la aplicación Configuracion Centralizada.*

## Resumen de pasos automatizados
*Readiness*
1. Validar el estado del servicio IIS en cada servidor.
2. Validar el estado de los siguientes Application Pools en cada servidor.

  - SegUnixOranServiceAppPool
  - ServicioCentral_WEB
  - ServicioCentral_WS
  - WSTransformadorXSLT

3. Validar el estado de la URL de Configuracion Centralizada, definida en inventory/env/group vars.

## Variables de Rol
El rol define la mayoría de sus variables en `vars/main.yml`.
Las variables adicionales son las siguientes:

***Variables de grupo:***
* `configcentralizada_pool_iis_name`: Lista de Application Pools de Configuración Centralizada.
    - **Tipo**: list
    - **Values**: `"ApplicationPool_names"`
    - **Required**: true

## Pruebas
*Las pruebas de estos roles fueron llevadas acabo directamente en los servidores de Configuración Centralizada.*