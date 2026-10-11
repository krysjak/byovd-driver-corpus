# `GSCAuxDriverx64_8.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `17D058085BF607710F97BE9C254FBB80AA9806D38A7A7857E0CF1992FF1AFE99` | `27D6673D86414BD166470FD3735FCB15D11A8CC6` | `0FEB7EA2C0C13FAC209531FE8D57F199` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_8.sys`
- **Розмір:** 86072 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Опис:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
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
