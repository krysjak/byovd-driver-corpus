# `RTKVHD64_10.sys`

[Назад до індексу](../README.uk.md) · [English version](RTKVHD64_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E7A9A9086C662D8613DACEBC2AFF6DCCDCE2F1EC49D9608570E9FF2F790BEA9A` | `4ED445BDB46B72ED8C595724318EBDAF6AB03CCA` | `8CC349A13E5FA7857A92F3DDFA2AA36D` |

## Метадані

- **Ім'я файлу:** `RTKVHD64_10.sys`
- **Розмір:** 7227992 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek(r) High Definition Audio Function Driver
- **Опис:** Realtek(r) High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
