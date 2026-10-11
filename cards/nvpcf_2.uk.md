# `nvpcf_2.sys`

[Назад до індексу](../README.uk.md) · [English version](nvpcf_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1A910336BF9627EA89600A7A08A96E25DD615C46C8DE2680FEA817D6DFDD2D1F` | `AFB2A2FB04F27B4062B72D283A38673A7F9F0EE1` | `B48EBE042D80D374973887A807FB4D74` |

## Метадані

- **Ім'я файлу:** `nvpcf_2.sys`
- **Розмір:** 235016 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVPCF
- **Опис:** NVIDIA Platform Controllers and Framework
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 115

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
