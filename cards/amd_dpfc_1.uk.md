# `amd_dpfc_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amd_dpfc_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `19E48CE439C7CEE4658DF7D3ADD6371FC3D70E57F6D3934AEFDAAE0D615D2A44` | `02B59EB74F2B0EE8E8FD25C7867CEDFB697246FB` | `52948042F4374E1A60657264BCFD0F6B` |

## Метадані

- **Ім'я файлу:** `amd_dpfc_1.sys`
- **Розмір:** 53120 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD Dynamic Power and Frequency Control Service Driver
- **Опис:** AMD Dynamic Power and Frequency Control Service Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 105

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
