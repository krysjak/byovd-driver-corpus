# `IntcAudioBus_4.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1421A779553E0FE99C62997EE3E3E47104C93190DF7DA42C389918D10768F570` | `F035478B6832F10500A3144BAAE56593FEFFE87C` | `B5E0BDDBAD508FDA5AA09A0076160F8A` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_4.sys`
- **Розмір:** 320952 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) Smart Sound Technology BUS
- **Опис:** Intel(R) Smart Sound Technology BUS
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
