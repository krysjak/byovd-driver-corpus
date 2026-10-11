# `igdkmd64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmd64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `372C424B7E97EF4E7E94440CD1E3193244CECF63C8AD4AD495C22207BA24C2B7` | `63CFAF78CCC316A0B09874010C9F7F8EEB778CC9` | `18F15C6123A0F6A854234FA01EF179EA` |

## Метадані

- **Ім'я файлу:** `igdkmd64_4.sys`
- **Розмір:** 20630888 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel HD Graphics Drivers for Windows(R)
- **Опис:** Intel Graphics Kernel Mode Driver
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
