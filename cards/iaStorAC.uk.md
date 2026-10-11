# `iaStorAC.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAC.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0DC0471FC9CD6029188579A6A81AE3C39228EC555F209A5F837548269B93893B` | `9D7B142F2EB7C7AAB9F441FFCB0F705887547CA3` | `7B5C66F6ED486974A7D0FF68E03C6CC5` |

## Метадані

- **Ім'я файлу:** `iaStorAC.sys`
- **Розмір:** 1545424 bytes
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
