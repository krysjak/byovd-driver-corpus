# `HECIx64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](HECIx64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2465DF47644BFEA249B2AD04F3443FD0494C82B5EAADB17E34325F989271EB1A` | `D776CB1C147CFACE2850336AADC0CD4129088164` | `E371FC5C4E76CE5313E68398F7950FB8` |

## Метадані

- **Ім'я файлу:** `HECIx64_1.sys`
- **Розмір:** 64512 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
