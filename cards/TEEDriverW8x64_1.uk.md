# `TEEDriverW8x64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW8x64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4846A29DD631E2E253560E7A28439AE11F244AB77F0C826AD56EA485577DBDD6` | `14F34C2F4C8B5F33A97EA1FA1FE411DBBEFA0496` | `296C443FCC228EA643ED310465772820` |

## Метадані

- **Ім'я файлу:** `TEEDriverW8x64_1.sys`
- **Розмір:** 184608 bytes
- **Архітектура:** 0x8664
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
