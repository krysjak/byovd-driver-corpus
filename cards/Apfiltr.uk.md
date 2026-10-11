# `Apfiltr.sys`

[Назад до індексу](../README.uk.md) · [English version](Apfiltr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3E677EB99A4496443EE2CA4803C1115680F08FA548ADBBA45D9267D450A589B0` | `A4D9F13C9C785CEAB74228E61AEEF83395CBD52F` | `3F2DA60B4640D16872415448913B01C9` |

## Метадані

- **Ім'я файлу:** `Apfiltr.sys`
- **Розмір:** 509696 bytes
- **Архітектура:** 0x14c
- **Компанія:** Alps Electric Co., Ltd.
- **Продукт:** Alps Touch Pad Driver
- **Опис:** Alps Touch Pad Driver
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
