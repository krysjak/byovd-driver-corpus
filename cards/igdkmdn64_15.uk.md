# `igdkmdn64_15.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdn64_15.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `20923EB4FBFE5DAAAC64A628765C86A52B4701F2BEAF3192DC59B01214D23612` | `F56EE24CBC4302C8CE1F812A5AA2847010CE6F0F` | `97B2583E28353177B79BBE12DA197DEA` |

## Метадані

- **Ім'я файлу:** `igdkmdn64_15.sys`
- **Розмір:** 28658760 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode New Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 130

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
