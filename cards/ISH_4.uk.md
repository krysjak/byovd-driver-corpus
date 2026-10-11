# `ISH_4.sys`

[Назад до індексу](../README.uk.md) · [English version](ISH_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B45D4E221F48221541E3844A9362AC364D1D8143B6ED70A338BBA8E89FBED6E7` | `C1E769E32BA1F177BCCFD49F9CC433B183F95398` | `AFDAC4240145325D526114A0D9E50A8A` |

## Метадані

- **Ім'я файлу:** `ISH_4.sys`
- **Розмір:** 175232 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel
- **Продукт:** ISS
- **Опис:** Intel(R) Integrated Sensor Solution
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
