# `TEEDriverGscW8x64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverGscW8x64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8C9F812139E234468E68B77DA6C80569D6E782D8C42555792A545449359BB440` | `437FE7195B8BB486D51D637EB59833E0ED476A24` | `AD6F6638FFAC51780A176AD30C7D4B1F` |

## Метадані

- **Ім'я файлу:** `TEEDriverGscW8x64_6.sys`
- **Розмір:** 280672 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
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
