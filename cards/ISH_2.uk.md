# `ISH_2.sys`

[Назад до індексу](../README.uk.md) · [English version](ISH_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8EAF758E6971DE895031F9857DA548B13999693A7BE5475C15CF66B4FAAB0F0E` | `86E14C97409C566C146750761295BA485F197679` | `58591E72C182B37FACD50238385EEC4A` |

## Метадані

- **Ім'я файлу:** `ISH_2.sys`
- **Розмір:** 169648 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel
- **Продукт:** ISS
- **Опис:** Intel(R) Integrated Sensor Solution
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
