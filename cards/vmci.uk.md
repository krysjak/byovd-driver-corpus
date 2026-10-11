# `vmci.sys`

[Назад до індексу](../README.uk.md) · [English version](vmci.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E9A45BDDB38925DED64B874644F58A6E8E87A10614ED7A34B9BDCCE6BD3D46C6` | `19FF3E6B7B988E2A14018B9B8705BE99172D6A1C` | `5B2F4B17924A5BD97EF2B7FFEC16059E` |

## Метадані

- **Ім'я файлу:** `vmci.sys` (Ідентичні копії: `vmci_1.sys`)
- **Розмір:** 106536 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Inc.
- **Продукт:** VMware PCI VMCI Bus Device
- **Опис:** VMware PCI VMCI Bus Device
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
