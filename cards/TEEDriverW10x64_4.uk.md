# `TEEDriverW10x64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10x64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A2E0B9EA4973BC875BAF685C684ED007407D05AB0BB053C3FB72D6357106A571` | `EDDC4FCB2CE978FD502A66F27226CD4910747A82` | `EAF180CED3A07245F238ED21D9C68975` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10x64_4.sys`
- **Розмір:** 323264 bytes
- **Архітектура:** 0x8664
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
