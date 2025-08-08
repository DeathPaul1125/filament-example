# 📦 Proyecto Demo - FilamentPHP

![Filament Logo](https://filamentphp.com/images/logo.svg)

> Proyecto de demostración basado en la documentación oficial de **[FilamentPHP](https://filamentphp.com/)**, utilizando Laravel y Livewire para la creación de paneles de administración modernos, rápidos y personalizables.

---

## 🚀 Descripción

Este proyecto es una implementación paso a paso del **demo oficial de Filament**, pensado para entender su estructura, componentes y flujo de trabajo.  
Es ideal para:

- Aprender cómo funciona Filament en Laravel.
- Experimentar con recursos, páginas y widgets.
- Tener una base para futuros proyectos con paneles administrativos.

---

## 📋 Requisitos previos

Antes de comenzar, asegúrate de tener instalado:

- [PHP 8.1+](https://www.php.net/)
- [Composer](https://getcomposer.org/)
- [Node.js 18+](https://nodejs.org/)
- [Laravel 10+](https://laravel.com/)
- Base de datos MySQL o PostgreSQL

---

## ⚙️ Instalación

Clona el repositorio y ejecuta los siguientes comandos:

```bash
# Clonar el proyecto
git clone https://github.com/usuario/filament-example.git
cd filament-example

# Instalar dependencias de PHP
composer install

# Instalar dependencias de Node.js
npm install && npm run build

# Configurar variables de entorno
cp .env.example .env

# Generar clave de aplicación
php artisan key:generate

# Ejecutar migraciones y datos de ejemplo
php artisan migrate --seed
