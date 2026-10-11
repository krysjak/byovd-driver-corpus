# `iaStorA_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorA_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0C6B684781D27F423D20186A40D7513DD6ABC38AD286D013791B37CBF5477A55` | `2E35581C262F81BA931EA0DB1962CCE268949FCC` | `71341219FBB4BAB7F2462C4267DAB594` |

## Метадані

- **Ім'я файлу:** `iaStorA_1.sys`
- **Розмір:** 644968 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel Rapid Storage Technology driver 
- **Опис:** Intel Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
