# `ibtpci.sys`

[Назад до індексу](../README.uk.md) · [English version](ibtpci.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F039D02E63B0E46A64E30A9B9F83D96913B456FDC90DC802A15366D69715A4A7` | `EF4A410B0643143F9B593ECC285C2C7DA11CB23D` | `1A04E3529586A6674975FD7396B773CD` |

## Метадані

- **Ім'я файлу:** `ibtpci.sys`
- **Розмір:** 19637144 bytes
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
