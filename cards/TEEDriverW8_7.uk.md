# `TEEDriverW8_7.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW8_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8273F2510EF4EA39AECBDA29ABA0FAB14B3D42FAFBB8811B789AFF0242BD6C59` | `7933CAF2132B4BD4C2395F830785010805B3ED92` | `A30C0B52EB63229C61ABA6CFC6B0966B` |

## Метадані

- **Ім'я файлу:** `TEEDriverW8_7.sys`
- **Розмір:** 244336 bytes
- **Архітектура:** 0x14c
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
