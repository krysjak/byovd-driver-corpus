# `IntcOED_3.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `12D5B143D4C0CB6D0D54180C6E81AEBEDEB28531B0CBCA066387A7770AEABE13` | `5E4B0C1CE3665C825EC517CBCD5416B619F08319` | `A0CCF433825DB61A87B7F6EA240F1741` |

## Метадані

- **Ім'я файлу:** `IntcOED_3.sys`
- **Розмір:** 1131896 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) OED
- **Опис:** Intel® Smart Sound Technology (Intel® SST) OED
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
