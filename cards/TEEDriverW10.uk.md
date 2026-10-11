# `TEEDriverW10.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F1D4E2C4AEBA9401AB87C77F2BBFD0D0F1E4667D6C6653A41F7C79822494CEAE` | `0E9066366B4CBFDE940B68B36D889934B3C74F9B` | `145C0A79671AD6ADFC18A0B65089C506` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10.sys`
- **Розмір:** 271328 bytes
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
