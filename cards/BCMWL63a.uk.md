# `BCMWL63a.SYS`

[Назад до індексу](../README.uk.md) · [English version](BCMWL63a.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `64CBE1AA061F0CC761A6D9E3C0E4C484EE09CACA932CB18D1947BC7D9F893BA3` | `E8BD3E75168E54BCBA3CDC89845722C3DCAF0CEE` | `E6618C2CAEEE8A2644FD46B98304954A` |

## Метадані

- **Ім'я файлу:** `BCMWL63a.SYS`
- **Розмір:** 7585280 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Corporation
- **Продукт:** Broadcom 802.11 Network Adapter wireless driver
- **Опис:** Broadcom 802.11 Network Adapter wireless driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
