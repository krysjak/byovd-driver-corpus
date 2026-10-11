# `dptf_cpu_2.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `70BCA8F97027CA50E3B942367F163EA742EDD41653F7EC1B94D73A0899C33B8E` | `362C880C333739C66E176C1BE460C3CD36097A4E` | `0F040FD1B30D634B0519AF5C6118BC74` |

## Метадані

- **Ім'я файлу:** `dptf_cpu_2.sys`
- **Розмір:** 76960 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Dynamic Tuning
- **Опис:** Intel(R) Dynamic Tuning CPU Participant
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
