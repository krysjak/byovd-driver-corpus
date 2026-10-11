# `ibtpci_1.sys`

[Назад до індексу](../README.uk.md) · [English version](ibtpci_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4EAC78D9D64F0A358C069A907966530799CCF2A4B6A7585A1B2EB3EE3F760CBF` | `6070F809453A7C29257C0549E176E4FCFCE10918` | `4497A04A809E3B5998ECDF2AE970F392` |

## Метадані

- **Ім'я файлу:** `ibtpci_1.sys`
- **Розмір:** 7831480 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Wireless Bluetooth(R)
- **Опис:** Intel(R) Wireless Bluetooth(R) PCIe Function Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
