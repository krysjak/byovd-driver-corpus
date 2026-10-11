# `IntcOED_11.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_11.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `80E310FE4ACCF88FB9EABE3DAE1E659BBEBA415302B354C491B104EC9E10BA5D` | `4DCC905A16A2634290B5295BAB07BE316539E7B4` | `63D433D6C561FCC54EEBC210B667BE72` |

## Метадані

- **Ім'я файлу:** `IntcOED_11.sys`
- **Розмір:** 742488 bytes
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
