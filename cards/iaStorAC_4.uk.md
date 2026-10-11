# `iaStorAC_4.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAC_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1F75F0539046C81F1895F1F0364F289059402CA833A6AF734CAF8A073ADB32C8` | `3A39BCF9CA3AAD60C2E7871CEFB007B02000CCA9` | `F71B21DFAC95DCF4B8711F6CE9EA3EDD` |

## Метадані

- **Ім'я файлу:** `iaStorAC_4.sys`
- **Розмір:** 1347776 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
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
