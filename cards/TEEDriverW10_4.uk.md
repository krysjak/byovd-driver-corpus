# `TEEDriverW10_4.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `95935FFC847E48FA26A325BE1F9C52097E34B3E12D5BAA299D804B4BBC1F7E8E` | `6AB85EA2897678762B296B4757000A416D5528DD` | `84977E3A703A4042EC0FAB9A410DB728` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10_4.sys`
- **Розмір:** 267976 bytes
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
