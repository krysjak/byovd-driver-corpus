# `cmgfve_1.sys`

[Назад до індексу](../README.uk.md) · [English version](cmgfve_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `818C6FAC8EA1CD24388EA34FE4BB8E4DE60A4B2471DCA4C565F9F3A82582D631` | `65DE14C8953E9D47C3D51993EC2A62573C5473B5` | `69BC760DA2EFE514CC1042B3B5C38224` |

## Метадані

- **Ім'я файлу:** `cmgfve_1.sys`
- **Розмір:** 210656 bytes
- **Архітектура:** 0x8664
- **Компанія:** Dell Inc.
- **Продукт:** CmgFVE.sys (64b,rls)
- **Опис:** Credant Full Volume Encryption Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 90

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
