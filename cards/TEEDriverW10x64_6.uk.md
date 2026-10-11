# `TEEDriverW10x64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10x64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `16E6C1F0C3146F0CF5B91CC591DD272A49E0141E6C45EC5EFB1645722EAC381B` | `483779DCDD6EF9F467FB10E8E11C04EC4A5B7912` | `08EE3F14784623C4B49FF048CB8EA000` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10x64_6.sys`
- **Розмір:** 308072 bytes
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
