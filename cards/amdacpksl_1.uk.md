# `amdacpksl_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2E0EB25C34B68480AA161DD20C94FF5878C47526904CEDA2648CB1F09D2B517D` | `68ACBB86088ADAAB15FAE63F5C4DC0811076C47A` | `12301DA47DC0FB3651E7D3197E7F7ACE` |

## Метадані

- **Ім'я файлу:** `amdacpksl_1.sys`
- **Розмір:** 353096 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD KSL Filter Driver
- **Опис:** AMD KSL Filter Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
