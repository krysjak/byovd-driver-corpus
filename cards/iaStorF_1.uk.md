# `iaStorF_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorF_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C2858590436EEDDE029C5448AEC3ACBB1C0FCED23F305302BAF831C6EC1654A` | `649E6520B7EF03F772C5F2E7206D305E3F42F8FE` | `B9D5AE799CB622C144AE5399C55EF29B` |

## Метадані

- **Ім'я файлу:** `iaStorF_1.sys`
- **Розмір:** 28008 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel Rapid Storage Technology Filter driver 
- **Опис:** Intel Rapid Storage Technology Filter driver - x64
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
