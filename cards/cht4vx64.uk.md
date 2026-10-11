# `cht4vx64.sys`

[Назад до індексу](../README.uk.md) · [English version](cht4vx64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9EC811C11EBF399A5C4FDDD07A9E63975F2145151306C8599F64DC35A0966EB0` | `39DD15E5B799B7EABA26D67AC38B583DB9CAF500` | `A31DAAEF9BA7D22DBFB68B7E9B17CD40` |

## Метадані

- **Ім'я файлу:** `cht4vx64.sys` (Ідентичні копії: `cht4vx64_1.sys`)
- **Розмір:** 1854880 bytes
- **Архітектура:** 0x8664
- **Компанія:** Chelsio Communications
- **Продукт:** Chelsio Communications Unified Network I/O Controller
- **Опис:** Virtual Bus Driver for Chelsio ® T5/T6 Chipset
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
