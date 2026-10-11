# `IntcOED_1.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A7D0D4E16E586966A9E2898DA3DFB7AA38700A10D31C036326D46FFED127B3BB` | `CB1543D86FFD37CBAB76477AB2980450B73EC2CF` | `B93BCEA86B99E9A356DB6B0B26E7B239` |

## Метадані

- **Ім'я файлу:** `IntcOED_1.sys`
- **Розмір:** 1283672 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) Smart Sound Technology OED
- **Опис:** Intel(R) Smart Sound Technology OED
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
