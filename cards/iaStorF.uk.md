# `iaStorF.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorF.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CB606F1A91D779324275A88FC0BFFA61E1552596BF08BB9A3455772BC867FC4F` | `CF01839D7E7E19ACEE4F48CB19C894D554191C89` | `B0EDD3C789CD3393CB1FA59657D901F2` |

## Метадані

- **Ім'я файлу:** `iaStorF.sys`
- **Розмір:** 25448 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel Rapid Storage Technology Filter driver 
- **Опис:** Intel Rapid Storage Technology Filter driver - x86
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
