# `TEEDriverW10_6.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `19BE751C49DFE9CE923085B4F4D9D1555B754C4C735272E76D3EE8D535703AE2` | `84FBE3F46B2E3A880679E3A09D0E8B5E6C750A67` | `330AFA77575F60BD628D78DFC5F6B22F` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10_6.sys`
- **Розмір:** 254856 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
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
