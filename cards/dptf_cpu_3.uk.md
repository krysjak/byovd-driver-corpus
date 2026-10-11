# `dptf_cpu_3.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EB97B9AE8AB841247F13A9CEC6CE6362B029FBF1960BAA2E50CC4E3A0A4398AF` | `73934EE08D24EC591E019843459D7BD394C74A94` | `734BF685B5E1843AE447165E25B42B70` |

## Метадані

- **Ім'я файлу:** `dptf_cpu_3.sys`
- **Розмір:** 73368 bytes
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
