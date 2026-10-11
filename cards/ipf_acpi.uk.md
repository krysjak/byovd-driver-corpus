# `ipf_acpi.sys`

[Назад до індексу](../README.uk.md) · [English version](ipf_acpi.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7C6F0BD4E7F68BF5130805BADD3C8703B7D95BA40D3D464A473C3C776996B8C4` | `5A6ADE3FC537B20FCA0501E6FBC4A9232937A5EA` | `3638B312FC8CBCA5E34B7C16CF131F66` |

## Метадані

- **Ім'я файлу:** `ipf_acpi.sys`
- **Розмір:** 90184 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Innovation Platform Framework
- **Опис:** Intel(R) Innovation Platform Framework ACPI Participant
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
