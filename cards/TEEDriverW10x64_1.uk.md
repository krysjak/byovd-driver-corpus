# `TEEDriverW10x64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10x64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4284462F0FDCBDDD13C2A86FD7508D5D16B57522C476CF7CFDD7141320FC7B5D` | `49D6143B2763220F817F84968CD1BE0EDAF2EFC3` | `0B84B5DE351B6E990A2F71FB7DA4536D` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10x64_1.sys`
- **Розмір:** 327648 bytes
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
