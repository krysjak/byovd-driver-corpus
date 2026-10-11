# `TEEDriverW10_3.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C14B796732E4ED65903A0FDE82B1D341435C32EC3B7CDCF5D8DE7E1523F66F6E` | `B7197020AA93742B4A4252F04C888972291B5EB0` | `277B9BE65B769565D2C88BF446539F1E` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10_3.sys`
- **Розмір:** 266336 bytes
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
