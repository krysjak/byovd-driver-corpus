# `nvpcf.sys`

[Назад до індексу](../README.uk.md) · [English version](nvpcf.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `221DFB195198FB1B417A27A911CB7E17ADC8007D50546149D0C5F1CB86BF1A9A` | `A0544B59C7C5C22C29E579B6D05F73637207B37E` | `62BD8F643D2FA264C10EE2A449A1F4C3` |

## Метадані

- **Ім'я файлу:** `nvpcf.sys`
- **Розмір:** 242816 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVPCF
- **Опис:** NVIDIA Platform Controllers and Framework
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 115

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
