# `igdkmdnd64_10.sys`

[Назад до індексу](../README.uk.md) · [English version](igdkmdnd64_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BC02EB0E8EAE50A5CFC29B322948866E4531D6F0A2C413F9ED5FA0FE7CC5C9E1` | `ACB13CE4903C9F44F13956CFC7F6CA4E96B9F89C` | `847AB0C8F7ED402565A9C0B7953C9858` |

## Метадані

- **Ім'я файлу:** `igdkmdnd64_10.sys`
- **Розмір:** 28658768 bytes
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
