# `TEEDriverW10_5.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `34026BB2D115F5F9867A05E6309FCD19D4B58480E71740C8989EB65AA406E3B0` | `DA7635D84E3A1ED1E114327DEE7EDE6E09698FF1` | `8BF4413DC76A755E18253FAECC6D1F16` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10_5.sys`
- **Розмір:** 263824 bytes
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
