# `igdkmdn64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdn64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5D0069A19017D6AE77EA2FECA3C60E6BB7175A6E4178310A9E7EBF20BE296F58` | `F4B38E8B90823E36DC2BC0A4B3F12E449387FFDB` | `67D7F9F01626641AD2B38D598758500A` |

## Метадані

- **Ім'я файлу:** `igdkmdn64_6.sys`
- **Розмір:** 19574120 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode New Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 165

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
