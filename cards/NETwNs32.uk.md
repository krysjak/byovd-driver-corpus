# `NETwNs32.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwNs32.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `494D5F5EE070E1BD719B9A50B11EE15DC4297C9D86B30C24579F782CEEF9100A` | `88219AC6C60CE73500FFBFB909D6E5FF966AB42C` | `D98BD0F579FE745CEF75E87EA88C4775` |

## Метадані

- **Ім'я файлу:** `NETwNs32.sys`
- **Розмір:** 7530736 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
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
