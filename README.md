# Abazeer — E-Commerce Platform

**A bilingual storefront with an admin panel built for daily operations.** Abazeer is a Laravel e-commerce platform: the storefront and its content are managed from a Filament admin panel, with Arabic and English side by side and an API for clients.

> This repository is a project showcase. It contains documentation only — the production source code is private.

---

## Overview

An e-commerce build where the back office does the heavy lifting: a large admin panel, bilingual content, media management, permissions and data import/export, on top of a Laravel API.

## My role

**Senior Laravel Backend Engineer**

- Built the backend and data model of the platform.
- Built the Filament admin panel and its resources, actions and permissions.
- Implemented the bilingual content model and the media pipeline.
- Built the API authentication and the social login flow.

## Tech stack

| Area | Stack |
| --- | --- |
| Language & framework | PHP 8.5, Laravel 13, MVC, Eloquent ORM |
| Admin panel | Filament 5, Livewire 4 |
| Styling | Tailwind CSS 4 |
| Data | MySQL, Redis |
| API & auth | Laravel Sanctum, Laravel Socialite |
| Content | spatie/laravel-translatable (Arabic / English), spatie/laravel-medialibrary |
| Permissions | Filament Shield, Spatie permissions |
| Data exchange | Laravel Excel (import / export) |
| Quality | PHPUnit test suite |
| Delivery | Git, CI/CD, Linux, Nginx |

## Key features

**Admin panel**
- 21+ Filament resources and 200+ actions covering the platform's day-to-day management.
- Navigation badges with counts and context, and a consistent design system across every screen.
- Global component styling, so toggles, badges and destructive actions behave the same everywhere.

**Bilingual content**
- Arabic and English content side by side, with a language switcher in the panel.
- Translatable fields handled at the model level.

**Media**
- A media library for images and files, attached to the records that use them.

**Permissions**
- Role-based access control generated per resource, so each role sees only what it should.

**Data exchange**
- Excel import and export for the records the team manages in bulk.

**Accounts and API**
- Social authentication for sign-in.
- Token-based API authentication with Sanctum.

**Quality**
- A PHPUnit test suite covering the platform's core behaviour.

## About this repository

This is a documentation-only showcase of a production product. It contains no client code, customer data or infrastructure details.

**Mohamed Karem Tawfik** — Senior PHP / Laravel Developer, Backend Team Lead
[GitHub](https://github.com/mkarem4) · [LinkedIn](https://linkedin.com/in/mohamed-karem93)
