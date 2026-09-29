# Servicio de autenticación · Fundación Huahuacuna

Microservicio de autenticación en NestJS y TypeScript para el proyecto Fundación Huahuacuna. Separa la lógica de acceso de usuarios de la aplicación web.

## Tecnologías

NestJS, TypeScript, Prisma y pnpm.

## Estructura

El proyecto está en [`auth-service-huahuacuna-master/auth-service-huahuacuna-master`](auth-service-huahuacuna-master/auth-service-huahuacuna-master). La lógica principal está en `src/auth`, con controlador, servicio, DTO y acceso a datos. También incluye configuración, comprobaciones de salud y pruebas.

## Desarrollo local

Dentro de la carpeta del proyecto:

```bash
pnpm install
pnpm run prisma:generate
pnpm run start:dev
```

Configura antes las variables de entorno y los servicios que requiera tu instalación. Este repositorio presenta el código del microservicio; no incluye un despliegue público de demostración.

## Proyecto relacionado

- [Aplicación web Huahuacuna](https://github.com/Kamilogallego/Huahuacuna-Code)
- [Servicio de donaciones](https://github.com/Kamilogallego/backend)
