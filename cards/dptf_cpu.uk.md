# `dptf_cpu.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `055E96F20FFFBCD1EDE806F3F816FDAA6FE91D16F792542CF76C8D727BFC394C` | `735788FB8431B85EC4E61BD6840B2D7980C77D9F` | `4EADF6F3F9CF90CCF0E3AC2E44E61B76` |

## Метадані

- **Ім'я файлу:** `dptf_cpu.sys`
- **Розмір:** 76936 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Dynamic Tuning
- **Опис:** Intel(R) Dynamic Tuning CPU Participant
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
