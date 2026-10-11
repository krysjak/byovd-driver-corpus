# `atihdw83.sys`

[Назад до індексу](../README.uk.md) · [English version](atihdw83.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FBD7E2BB1E07F3256899026FE5B7124B85051E9E215FC854DD41182D9D850961` | `4181AEEB488311666025392161B1F4E2BCB9C919` | `AFCCDF772532B2D431C363057A3757DB` |

## Метадані

- **Ім'я файлу:** `atihdw83.sys`
- **Розмір:** 196608 bytes
- **Архітектура:** 0x14c
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD HD Audio Driver
- **Опис:** AMD High Definition Audio Function Driver
- **Підпис:** unsigned
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
