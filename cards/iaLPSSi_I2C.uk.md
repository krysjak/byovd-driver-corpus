# `iaLPSSi_I2C.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSSi_I2C.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8445E41BAB21964C7F014742795E462BDDC6C37A261990B3D6BF4E637A719547` | `B226F7E4189BF32E6159BBF54C304753E6610633` | `EB82A11613326691508D9ED9A4FE29E7` |

## Метадані

- **Ім'я файлу:** `iaLPSSi_I2C.sys` (Ідентичні копії: `iaLPSSi_I2C_1.sys`)
- **Розмір:** 113152 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO I2C Controller Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
