# `UcmCxUcsiNvppc_1.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmCxUcsiNvppc_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `01736D4B848B3614EA4F88985C7836E6403794A3D769DDCF9597F868F75B29FC` | `D58478D2A781B8A18CA8419A1DBFD3A1D4D7CDAE` | `BADAB706325D4DC994F9934FC6BF3222` |

## Метадані

- **Ім'я файлу:** `UcmCxUcsiNvppc_1.sys`
- **Розмір:** 715296 bytes
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
