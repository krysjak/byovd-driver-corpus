# `CmgFFE.sys`

[Назад до індексу](../README.uk.md) · [English version](CmgFFE.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `209694217C5199EA31C403B3F5E1678429DDAD4A6916F1B2275CCD28D64294F3` | `182A3704377AA3E84823AEBCD182A933120FEE7B` | `FD6BE30252F02CC333B5348DAB6A8146` |

## Метадані

- **Ім'я файлу:** `CmgFFE.sys`
- **Розмір:** 644064 bytes
- **Архітектура:** 0x14c
- **Компанія:** Dell Inc.
- **Продукт:** Dell Data Protection Encryption
- **Опис:** Credant File & Folder Encryption Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
