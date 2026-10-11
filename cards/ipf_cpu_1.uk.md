# `ipf_cpu_1.sys`

[Назад до індексу](../README.uk.md) · [English version](ipf_cpu_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `94C8F59C816A477E6A3F17E02863DBBBAF0241B2A96010CBF7FA406DB2785686` | `ABEF78F622360C0B3C5D933A5A2893568CC957EE` | `26EDB48D962EB1DCE5E92E1E0C83B69C` |

## Метадані

- **Ім'я файлу:** `ipf_cpu_1.sys`
- **Розмір:** 79512 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Innovation Platform Framework
- **Опис:** Intel(R) Innovation Platform Framework CPU Participant
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
