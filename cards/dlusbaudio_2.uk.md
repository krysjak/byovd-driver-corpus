# `dlusbaudio_2.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FF3E55E378B443F347CA972DDC597CA056041C1507172807C409DC434FB9C597` | `08ED7F089DDB2941B644BBCFCE8C1842894C0A4D` | `C91FB4A53E3A39B35747563D69C8FCBC` |

## Метадані

- **Ім'я файлу:** `dlusbaudio_2.sys`
- **Розмір:** 168280 bytes
- **Архітектура:** 0x14c
- **Компанія:** DisplayLink Corp.
- **Продукт:** DisplayLink USB Audio 2.0 Class Driver
- **Опис:** DisplayLink USB Audio Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
