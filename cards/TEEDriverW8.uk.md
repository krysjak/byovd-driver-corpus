# `TEEDriverW8.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A052592A8110534A4F98A970A89C98D3AE5B1B95A13EA452593457FDBD6C6F14` | `91505929AA615BD6C483CACB9F4B68EB141C1953` | `51A192A702DB46678A70C4E9162CAC07` |

## Метадані

- **Ім'я файлу:** `TEEDriverW8.sys`
- **Розмір:** 247696 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
