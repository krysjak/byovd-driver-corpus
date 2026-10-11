# `amdi2c.sys`

[Назад до індексу](../README.uk.md) · [English version](amdi2c.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6EA32494A758ED615C1123D590E2BF95BBAC0C075FD913B7F8A9910441BC3B9D` | `B1580173425335AA4AF446D8AEFEA0361844F36D` | `18704304D13099948EF262501814FC41` |

## Метадані

- **Ім'я файлу:** `amdi2c.sys` (Ідентичні копії: `amdi2c_1.sys`, `amdi2c_2.sys`)
- **Розмір:** 84264 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD I2C Controller Driver
- **Опис:** AMD I2C Controller Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11 · **Задокументовано:** 2024-08-15
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** In the wild
- **Score:** 0 · **MITRE:** T1068

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

**Опис:** 

```
sc.exe create TfSysMon.sys binPath=C:\windows\temp\TfSysMon.sys type=kernel && sc.exe start TfSysMon.sys
```

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
