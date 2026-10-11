# `TeeDriverGscW8x64.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverGscW8x64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D9652679116E277BA8A0110D4ED06B4FC380106882D914DE387557EEB726BAF2` | `994712735E1091BB06E766CE2700DDA2CEB9EFF1` | `AA16C46FC2AAA545A2EFCA92F18507E4` |

## Метадані

- **Ім'я файлу:** `TeeDriverGscW8x64.sys`
- **Розмір:** 251152 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
