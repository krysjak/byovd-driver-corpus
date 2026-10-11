# `igdkmdn64_10.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdn64_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `269BFC9F919E2316BCB7ABF51EB0BE7BED3F8F39B7D77B2AA563CFC678E792BC` | `464AFEC962A0A56A78ADA6A06D863581ED30EA7E` | `A7BC91D8DE46A18848A0C24494F51CF7` |

## Метадані

- **Ім'я файлу:** `igdkmdn64_10.sys`
- **Розмір:** 40284224 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode New Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 160

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
