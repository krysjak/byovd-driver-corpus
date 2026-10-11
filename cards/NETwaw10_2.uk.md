# `NETwaw10_2.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwaw10_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D821F2A91F8AFA523EA4A98632CF23331552807881F89024D6A0B86977F6497E` | `27DA15C87BF783FD7B95FF75A51A2B0EEA593C5D` | `681775933DB3765754F74E5CC5702FC6` |

## Метадані

- **Ім'я файлу:** `NETwaw10_2.sys`
- **Розмір:** 4889168 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** R Intel Wireless WiFi Link Driver
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
