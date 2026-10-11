# `iaStorVD_3.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorVD_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C2AF187D0E32380B9AE552DD94AC8B788D346889A21D2EE0C9D1DB64690F4CE` | `A00E888B7D48C3BC50F2505A4BCF7142C41748B3` | `688BDC09B13B3F4C0462E3AEB568E713` |

## Метадані

- **Ім'я файлу:** `iaStorVD_3.sys`
- **Розмір:** 1605296 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
