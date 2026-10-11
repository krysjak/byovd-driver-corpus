# `igdkmdn64_5.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdn64_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `114D6084E53909BBFF92880A14A17C15083ECB335C0F79C4FB865DB30BE565F2` | `04F5C58217A9555552A3EC8C2E1E783749D6C0F4` | `CDDDB0726AB7CF49A47DABC0E3048963` |

## Метадані

- **Ім'я файлу:** `igdkmdn64_5.sys`
- **Розмір:** 50821928 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode New Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 180

## Профіль можливостей

**Primitives:** `MDL allocation`, `arbitrary memory copy`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmCopyMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
