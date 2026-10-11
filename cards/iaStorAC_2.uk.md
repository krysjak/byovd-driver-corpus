# `iaStorAC_2.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAC_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E8A59332484020532073851F04DD759FCB135C600AF4CE81561C3D153990DB23` | `F2E5E1507CAD1ECE88EBBA251B868C0B9A206600` | `EF85A43F9E5CF62B399BF334C9F8D32A` |

## Метадані

- **Ім'я файлу:** `iaStorAC_2.sys`
- **Розмір:** 1347464 bytes
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
