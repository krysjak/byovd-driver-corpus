# `WiMan.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `819C2F1CB0367B4C7A4CE6AD834E04647E5C3F4DB6CAE7B39D0F79C959C9EE0E` | `4A693AC2F6A55C78D475215E43ACC524D655C0ED` | `54C29AD4268F56C07351EB3CEA078F71` |

## Метадані

- **Ім'я файлу:** `WiMan.sys`
- **Розмір:** 171952 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless Manageability
- **Опис:** Intel® Wireless Manageability
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
