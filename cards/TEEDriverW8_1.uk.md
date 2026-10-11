# `TEEDriverW8_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW8_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EE970B70136F47ED5F4FC32EC83FF1DD2E11F2228FC91F077151FE7AF927A7BC` | `5A3C763DF11AB784F5474A8D3D9AC7A5B02439E4` | `75A24FF735BCA61F38C24F88D1E4D34C` |

## Метадані

- **Ім'я файлу:** `TEEDriverW8_1.sys`
- **Розмір:** 162080 bytes
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
