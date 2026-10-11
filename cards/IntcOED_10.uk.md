# `IntcOED_10.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D1AE399AEEE2AD0683D26AA51355931C58B982A9ED0B884BC0D5E3919E069CF1` | `ACC1C5B5F5D2F726D92421308E8721698FDCAB7C` | `59F87E546EA4376250B71532B7281A63` |

## Метадані

- **Ім'я файлу:** `IntcOED_10.sys`
- **Розмір:** 1168456 bytes
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
