# `TbtBusDrv_4.sys`

[Назад до індексу](../README.uk.md) · [English version](TbtBusDrv_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6127D33E6CA8A104F646EAD60ED95EEE482FD082156FC746D6DC9D18E7D57588` | `CABE068F36C44191EDFEC5833C60D2F89AC1B4B3` | `5471075EB777F38C49E8E39D2E675BE2` |

## Метадані

- **Ім'я файлу:** `TbtBusDrv_4.sys`
- **Розмір:** 2141456 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Thunderbolt(TM) Bus Driver
- **Опис:** Thunderbolt(TM) Bus Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
