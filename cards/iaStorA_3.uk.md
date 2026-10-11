# `iaStorA_3.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorA_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `974A5CCAFD0A514D45838F330121095195D57CF9295B5FD790F6E73A95A9C4C0` | `FF78F402604619DE61CF76B8E9ECDB275A6DE310` | `62EECD3225EF2B5649780746928F5CF7` |

## Метадані

- **Ім'я файлу:** `iaStorA_3.sys`
- **Розмір:** 1468416 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
