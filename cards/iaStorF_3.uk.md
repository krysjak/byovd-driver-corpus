# `iaStorF_3.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorF_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C0F2223CC80F23028AE6BE6784B0ACA0CCBCE289A00B0E3A5AB888055703A226` | `3EC0E7D068A4A83FFE0400DF5D32D0D662BEB7C7` | `E54EFF634E76F51FC96F32AFF33A0DD2` |

## Метадані

- **Ім'я файлу:** `iaStorF_3.sys`
- **Розмір:** 31712 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology Filter driver 
- **Опис:** Intel(R) Rapid Storage Technology Filter driver - x64
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
