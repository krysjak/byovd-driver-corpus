# `ipoib6x.sys`

[Назад до індексу](../README.uk.md) · [English version](ipoib6x.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `585BF746BF943E5F0FD09C6CF3B96643BB1E4B9D0489D205E11A99F7742E6444` | `0EC1D57A625E5407113FD253130909700AB1CEEE` | `A73BA5D0E080002650F0FFFFF01C4DFE` |

## Метадані

- **Ім'я файлу:** `ipoib6x.sys`
- **Розмір:** 579376 bytes
- **Архітектура:** 0x8664
- **Компанія:** Mellanox
- **Продукт:** MLNX_EN
- **Опис:** Mellanox ConnectX based IPoIB Adapter ( NDIS 6.4) Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
