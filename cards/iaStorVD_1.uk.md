# `iaStorVD_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorVD_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D2F5E62F6717E9DF8925E29B4B8789316505CB2D8B6EA0D22104249F692B7C8` | `EA6F13E7031BBCC5317519F288FDA8DBFF255BA5` | `514A0D2FCA07453604D8DD26B34A5961` |

## Метадані

- **Ім'я файлу:** `iaStorVD_1.sys`
- **Розмір:** 1623632 bytes
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
