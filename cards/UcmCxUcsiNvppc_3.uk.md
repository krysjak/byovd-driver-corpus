# `UcmCxUcsiNvppc_3.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmCxUcsiNvppc_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `713A90D2C71845D7E8F080A930ED947F00AC18E6139AF81350B45418422E2C17` | `4E32B114ABD1CA53BE25A177696B10ADC12B61D1` | `73B0BCEF412F54C9C8C6480E31007981` |

## Метадані

- **Ім'я файлу:** `UcmCxUcsiNvppc_3.sys`
- **Розмір:** 713304 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVPPC
- **Опис:** NVIDIA PPC Function Driver.
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
