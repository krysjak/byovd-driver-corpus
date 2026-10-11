# `igdkmdn64_14.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdn64_14.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CF5C61851037FBE3B7289CFD2EE81DECB41D62AD8A9047DA810E2F3AE4307F90` | `45BC0B72255D272B65952348BA43A7895A1BC5ED` | `886B4E89637A5062DE7976FC8A46D487` |

## Метадані

- **Ім'я файлу:** `igdkmdn64_14.sys`
- **Розмір:** 28658744 bytes
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
