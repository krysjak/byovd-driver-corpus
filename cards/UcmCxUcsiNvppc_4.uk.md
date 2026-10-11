# `UcmCxUcsiNvppc_4.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmCxUcsiNvppc_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6C56B6EA774835C65EC9F246F216EC34A3EE3BB56DF4FFA37416788FA35B8242` | `8FBE86C484B042FE7CCB48D857A856A26BC5BBBC` | `A42981D9B3D60C51AE7E27C3EDDCEAA2` |

## Метадані

- **Ім'я файлу:** `UcmCxUcsiNvppc_4.sys`
- **Розмір:** 713328 bytes
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
