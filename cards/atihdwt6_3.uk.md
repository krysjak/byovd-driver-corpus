# `atihdwt6_3.sys`

[Назад до індексу](../README.uk.md) · [English version](atihdwt6_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F6CFB657EF0488959A637459DF2278419ABA3DEDDEF731156DCBD5DBB3C5817E` | `0BA77854DD164577E30191D7E75C513F4AB34513` | `08D3A5CE2FE501438099002524E26E5F` |

## Метадані

- **Ім'я файлу:** `atihdwt6_3.sys`
- **Розмір:** 107936 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD HD Audio Driver
- **Опис:** AMD High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
