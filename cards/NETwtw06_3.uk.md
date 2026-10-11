# `NETwtw06_3.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw06_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `41A7819D6BA1FE9A92612A85E112DF6F565B2D61B529A0E15F85F880174C9470` | `E1BED75C5E7ACCD87E99F74AFCD832942FEB89EA` | `CA50241E1E5E21178C15EEF4519AB09C` |

## Метадані

- **Ім'я файлу:** `NETwtw06_3.sys`
- **Розмір:** 8899176 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
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
