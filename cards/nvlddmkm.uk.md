# `nvlddmkm.sys`

[Назад до індексу](../README.uk.md) · [English version](nvlddmkm.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C28FD719733F0AF2E56D48EF0EF1ABE67E6FA71972D870C2F03D2D66FCC509F0` | `E3D8D4E4171D9587CA15EF33CB99D3ADE86A5BE5` | `412CB552E064341DC5F43B2772563B89` |

## Метадані

- **Ім'я файлу:** `nvlddmkm.sys`
- **Розмір:** 120332520 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVIDIA Windows Kernel Mode Driver, Version 610.88 
- **Опис:** NVIDIA Windows Kernel Mode Driver, Version 610.88 
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`, `process handle access`, `process lookup`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwMapViewOfSection`, `ZwOpenProcess`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
