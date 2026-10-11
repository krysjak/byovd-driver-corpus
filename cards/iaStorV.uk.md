# `iaStorV.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorV.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7E862C0367B382ADE309DEA6BEB95FD2EED15CAE8BDDA37658D66484C00F88BB` | `95DFC01672BB6667FC3AE4F9C1E349385F31B25F` | `061FA45F59C7328C4749B0E5BAA9FC52` |

## Метадані

- **Ім'я файлу:** `iaStorV.sys` (Ідентичні копії: `iaStorV_1.sys`)
- **Розмір:** 413088 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel Matrix Storage Manager driver
- **Опис:** Intel Matrix Storage Manager driver - x64
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
