# `iaStorF_2.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorF_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0487990C54851DE824196E1E2E859C4A4E9C90896CFD97141E0445A72FC18446` | `806888DF30D7C7E4DFA56901122A296ABDEC8DF0` | `80CA8D11B20F6DE39BE00875636C3C8E` |

## Метадані

- **Ім'я файлу:** `iaStorF_2.sys`
- **Розмір:** 28128 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology Filter driver 
- **Опис:** Intel(R) Rapid Storage Technology Filter driver - x86
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
