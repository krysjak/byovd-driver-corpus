# `amdpsp_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amdpsp_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `353AB70AE1E174A5E9B908B1F73B5D9760CAD5F6A24EBC0CF60C18723BD314FF` | `065FFDD7244BA2C062CD457DC3DEFB7D313C5FBE` | `EDDE442DCE6DC0BEC4721365D6ACBC9C` |

## Метадані

- **Ім'я файлу:** `amdpsp_1.sys` (Ідентичні копії: `amdpsp_3.sys`)
- **Розмір:** 60224 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc. 
- **Продукт:** Advanced Micro Devices, Inc. amdpsp sys
- **Опис:** amdpsp sys
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
