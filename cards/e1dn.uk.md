# `e1dn.sys`

[Назад до індексу](../README.uk.md) · [English version](e1dn.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `07A97BADAF775CEEC177F3B472AA6EEF878584B6A8CA5132EE3E36D4C5065EBA` | `EE759FB286CC673EACB77B8D719E24A04FD96E0E` | `71EA94952E2E21CD514A99FB86503F1F` |

## Метадані

- **Ім'я файлу:** `e1dn.sys`
- **Розмір:** 1739360 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Ethernet Connection I219
- **Опис:** Intel(R) Ethernet Controller (NetAdapterCx 2.2)
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
