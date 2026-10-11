# `amdacpbus.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpbus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `915F7B818BBEB3F0B879AFF30C62EB981641B1616B63F0A629FF87E79757287C` | `F650058A3FACEDF4DFCAFB72EA7CD72852394D25` | `6E7715E96AA5C573CDACC8F1B1117E3D` |

## Метадані

- **Ім'я файлу:** `amdacpbus.sys`
- **Розмір:** 1386912 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD Audio CoProcessor
- **Опис:** AMD Audio CoProcessor
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
