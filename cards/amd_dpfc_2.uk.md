# `amd_dpfc_2.sys`

[Назад до індексу](../README.uk.md) · [English version](amd_dpfc_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `852EEBACDBF7CC314B1FCE5560230B4AA9F23C16F41056ED6DA246E15ABE9A0F` | `DA10E94DC3A8F7F119B101BE87CEB43434978EF9` | `85708C3CB9CA2CAE50F5B65D9AD2B58D` |

## Метадані

- **Ім'я файлу:** `amd_dpfc_2.sys`
- **Розмір:** 59072 bytes
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
