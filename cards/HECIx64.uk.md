# `HECIx64.sys`

[Назад до індексу](../README.uk.md) · [English version](HECIx64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D69F522EEE764AAFA4BB1520778BFA59F3DFEB87453F76672BF9B605E5B5C711` | `4BE472294B90B4EB8E8D7751E8D43C3E19E5622D` | `F1A67CF6EA9DD11BFC730AB990C67D97` |

## Метадані

- **Ім'я файлу:** `HECIx64.sys`
- **Розмір:** 64472 bytes
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
