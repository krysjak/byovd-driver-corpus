# `iaLPSS2_UART2_MTL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_UART2_MTL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `74C72D631D98F9ACA9C9459F411DC5E5F129BF64CFABE3CDBEFA0E7E17551C70` | `58B393B5A65DE6434E9E62D8DA8C0EF9ECC90994` | `4D5098ADFBBA2C92DD1CFA58EBE012C0` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_UART2_MTL.sys`
- **Розмір:** 322560 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO UART Driver
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
