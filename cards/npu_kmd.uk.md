# `npu_kmd.sys`

[Назад до індексу](../README.uk.md) · [English version](npu_kmd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A06669F848BDF897B6042D1C2082AB71123F0CB362A4CE2641A5C6F70B242018` | `57B6C619ED61E90152492D1B8BFF04F29A661020` | `0A3189640984010926FBD6BCA30C0369` |

## Метадані

- **Ім'я файлу:** `npu_kmd.sys`
- **Розмір:** 3871712 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) NPU Driver
- **Опис:** Kernel Mode Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 65

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `driver loading`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
