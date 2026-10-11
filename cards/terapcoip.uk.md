# `terapcoip.sys`

[Назад до індексу](../README.uk.md) · [English version](terapcoip.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `87B899E9CA4F7C56B05B1CD3BCCE4E288D60BA611D63D60EF0FBF9E9D156A52D` | `A674A10732452307D0EA34DF40E47077E6799F76` | `91B338AF46117DD60A2FE902DAFF77B9` |

## Метадані

- **Ім'я файлу:** `terapcoip.sys`
- **Розмір:** 97792 bytes
- **Архітектура:** 0x14c
- **Компанія:** Windows (R) Win 7 DDK provider
- **Продукт:** Windows (R) Win 7 DDK driver
- **Опис:** PCoIP(R) Device
- **Підпис:** unsigned
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
