# `TeeDriverW8x64_5.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8x64_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BFCB9F00A56788DD24602ABD9BA9E10F0E5D3DDD19425B8FF19DE3D1A98204CF` | `580BE09189C135C8EE620FD3C49BE516C102BBBA` | `314C3C98BC5F3B02F8427139133573C7` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8x64_5.sys`
- **Розмір:** 266128 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
