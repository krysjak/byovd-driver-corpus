# `IntcOED_6.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `898E935522E3BCA28741D8391A17783721AA63C20162FD97C9B2CA123AA8185A` | `272A6B99205319D5A27D4F6B9AFE54CD9E843C0D` | `26BC16E6C7AEC2104E8005543DCB3F4F` |

## Метадані

- **Ім'я файлу:** `IntcOED_6.sys`
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
