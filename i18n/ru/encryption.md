---
meta_title: "Recommended Encryption Software: VeraCrypt, Cryptomator, PicoCrypt, and OpenPGP - Privacy Guides"
title: "Инструменты для шифрования"
icon: material/file-lock
description: Шифрование данных - единственный способ контролировать доступ к ним. These tools allow you to encrypt your emails and any other files.
cover: encryption.webp
---

Шифрование данных - единственный способ контролировать доступ к ним. Если вы еще не используете какие-либо инструменты шифрования диска, электронной почты или файлов, то вы можете выбрать один из них тут.

## Мультиплатформенные приложения

Перечисленные здесь программы являются многоплатформенными и отлично подходят для создания зашифрованных резервных копий ваших данных.

### Cryptomator (Облако)

<div class="admonition recommendation" markdown>

![Логотип Cryptomator](assets/img/encryption-software/cryptomator.svg){ align=right }

**Cryptomator** - это программа для шифрования, разработанная для приватного хранения файлов в любом облачном хранилище. Программа может создавать хранилища в виртуальном диске, содержимое которых зашифровано и синхронизировано с твоим облачным хранилищем.

[:octicons-home-16: Homepage](https://cryptomator.org){ .md-button .md-button--primary }
[:octicons-eye-16:](https://cryptomator.org/privacy){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://docs.cryptomator.org){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/cryptomator){ .card-link title="Source Code" }
[:octicons-heart-16:](https://cryptomator.org/donate){ .card-link title=Contribute }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=org.cryptomator)
- [:simple-appstore: App Store](https://apps.apple.com/app/id1560822163)
- [:simple-android: Android](https://cryptomator.org/android)
- [:simple-windows11: Windows](https://cryptomator.org/downloads)
- [:simple-apple: macOS](https://cryptomator.org/downloads)
- [:simple-linux: Linux](https://cryptomator.org/downloads)
- [:simple-flathub: Flathub](https://flathub.org/apps/details/org.cryptomator.Cryptomator)

</details>

</div>

Cryptomator использует шифрование AES-256 для шифрования как файлов, так и их имён. Cryptomator не может зашифровать метаданные, такие как: время создания, изменения и доступа к файлу, количество и размер файлов и папок.

Cure53 провёл [аудит](https://community.cryptomator.org/t/has-there-been-a-security-review-audit-of-cryptomator/44) некоторых криптографических библиотек Cryptomator. Эти библиотеки включают в себя [cryptolib](https://github.com/cryptomator/cryptolib), [cryptofs](https://github.com/cryptomator/cryptofs), [siv-mode](https://github.com/cryptomator/siv-mode) и [cryptomator-objc-cryptor](https://github.com/cryptomator/cryptomator-objc-cryptor). Аудит не проходила [cryptolib-swift](https://github.com/cryptomator/cryptolib-swift), которая сейчас используется в iOS.

Cryptomator's documentation details its intended [security target](https://docs.cryptomator.org/en/latest/security/security-target), [security architecture](https://docs.cryptomator.org/en/latest/security/architecture), and [best practices](https://docs.cryptomator.org/en/latest/security/best-practices) for use in further detail.

### Picocrypt (Файлы)

<div class="admonition recommendation" markdown>

![Логотип Picocrypt](assets/img/encryption-software/picocrypt.svg){ align=right }

**Picocrypt** - это маленькая и простая программа, предоставляющая современное шифрование. Picocrypt использует безопасный шифр XChaCha20 и функцию формирования ключа Argon2id для обеспечения высокого уровня безопасности. Для функций шифрования он использует стандартные модули Go x/crypto.

[:octicons-repo-16: Repository](https://github.com/Picocrypt/Picocrypt){ .md-button .md-button--primary }
[:octicons-code-16:](https://github.com/Picocrypt/Picocrypt){ .card-link title="Source Code" }
[:octicons-heart-16:](https://opencollective.com/picocrypt){ .card-link title=Contribute }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-windows11: Windows](https://github.com/Picocrypt/Picocrypt/releases)
- [:simple-apple: macOS](https://github.com/Picocrypt/Picocrypt/releases)
- [:simple-linux: Linux](https://github.com/Picocrypt/Picocrypt/releases)

</details>

</div>

### VeraCrypt (Диск)

<div class="admonition recommendation" markdown>

![Логотип VeraCrypt](assets/img/encryption-software/veracrypt.svg#only-light){ align=right }
![Логотип VeraCrypt](assets/img/encryption-software/veracrypt-dark.svg#only-dark){ align=right }

**VeraCrypt** - это свободно распространяемая утилита с исходным кодом, используемая для шифрования "на лету". Программа может создавать виртуальный зашифрованный диск в файле, зашифровать логический раздел или даже зашифровать все устройство с предзагрузочной аутентификацией.

[:octicons-home-16: Homepage](https://veracrypt.fr){ .md-button .md-button--primary }
[:octicons-info-16:](https://veracrypt.fr/en/Documentation.html){ .card-link title=Documentation}
[:octicons-code-16:](https://veracrypt.fr/code){ .card-link title="Source Code" }
[:octicons-heart-16:](https://veracrypt.fr/en/Donation.html){ .card-link title=Contribute }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-windows11: Windows](https://veracrypt.fr/en/Downloads.html)
- [:simple-apple: macOS](https://veracrypt.fr/en/Downloads.html)
- [:simple-linux: Linux](https://veracrypt.fr/en/Downloads.html)

</details>

</div>

VeraCrypt - это форк, прекратившего свое существование, проекта TrueCrypt. По словам разработчиков, были реализованы улучшения безопасности и решены проблемы, найденные в ходе первоначального аудита кода TrueCrypt.

При шифровании с помощью VeraCrypt ты можешь выбрать различные [хэш-функции](https://en.wikipedia.org/wiki/VeraCrypt#Encryption_scheme). Мы настоятельно рекомендуем выбрать **только** [SHA-512](https://en.wikipedia.org/wiki/SHA-512) и блочное шифрование по алгоритму [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard).

Аудит Truecrypt проводился [несколько раз](https://en.wikipedia.org/wiki/TrueCrypt#Security_audits). Veracrypt [проходил](https://en.wikipedia.org/wiki/VeraCrypt#VeraCrypt_audit) аудит уже отдельно.

## Шифрование всего диска

For encrypting the drive your operating system boots from, we generally recommend enabling the encryption software that comes with your operating system rather than using a third-party tool. This is because your operating system's native encryption tools often make use of OS and hardware-specific features like the [secure cryptoprocessor](https://en.wikipedia.org/wiki/Secure_cryptoprocessor) in your device to protect your computer against more advanced physical attacks. For secondary drives and external drives which you *don't* boot from, we still recommend using open-source tools like [VeraCrypt](#veracrypt-disk) over the tools below, because they offer additional flexibility and let you avoid vendor lock-in.

### BitLocker

<div class="admonition recommendation" markdown>

![Логотип BitLocker](assets/img/encryption-software/bitlocker.png){ align=right }

**BitLocker** - решение для полного шифрования диска в Microsoft Windows. The main reason we recommend it for encrypting your boot drive is because of its [use of TPM](https://learn.microsoft.com/windows/security/information-protection/tpm/how-windows-uses-the-tpm). ElcomSoft, a forensics company, has written about this feature in [Understanding BitLocker TPM Protection](https://blog.elcomsoft.com/2021/01/understanding-BitLocker-tpm-protection).

[:octicons-info-16:](https://learn.microsoft.com/windows/security/information-protection/BitLocker/BitLocker-overview){ .card-link title=Documentation}

</details>

</div>

BitLocker is [only supported](https://support.microsoft.com/windows/turn-on-device-encryption-0c453637-bc88-5f74-5105-741561aae838) on Pro, Enterprise and Education editions of Windows. Эту функцию можно включить и в Home версии при соответствии условиям.

<details class="example" markdown>
<summary>Enabling BitLocker on Windows Home</summary>

To enable BitLocker on "Home" editions of Windows, you must have partitions formatted with a [GUID Partition Table](https://en.wikipedia.org/wiki/GUID_Partition_Table) and have a dedicated TPM (v1.2, 2.0+) module. You may need to [disable the non-Bitlocker "Device encryption" functionality](https://discuss.privacyguides.net/t/enabling-bitlocker-on-the-windows-11-home-edition/13303/5) (which is inferior because it sends your recovery key to Microsoft's servers) if it is enabled on your device already before following this guide.

1. Откройте командную строку и проверьте формат таблицы разделов диска с помощью следующей команды. Вы должны увидеть "**GPT**" в разделе "Стиль раздела":

    ```powershell
    powershell Get-Disk
    ```

2. Выполните эту команду (в командной строке от имени администратора), чтобы проверить версию вашего TPM. Вы должны увидеть `2.0` или `1.2`, перечисленные рядом с `SpecVersion`:

    ```powershell
    powershell Get-WmiObject -Namespace "root/cimv2/security/microsofttpm" -Class WIN32_tpm
    ```

3. Access [Advanced Startup Options](https://support.microsoft.com/windows/advanced-startup-options-including-safe-mode-b90e7808-80b5-a291-d4b8-1a1af602b617). Необходимо перезагрузиться, нажав клавишу F8 до запуска Windows, и перейти в *командную строку* в разделе **Устранение неполадок** → **Дополнительные параметры** → **Командная строка**.
4. Войдите под учетной записью администратора и введите следующее для запуска шифрования:

    ```powershell
    manage-bde -on c: -used
    ```

5. Закройте командную строку и продолжите обычную загрузку в Windows.
6. Откройте командную строку от имени администратора и выполните следующие команды:

    ```powershell
    manage-bde c: -protectors -add -rp -tpm
    manage-bde -protectors -enable c:
    manage-bde -protectors -get c: > %UserProfile%\Desktop\BitLocker-Recovery-Key.txt
    ```

<div class="admonition tip" markdown>
<p class="admonition-title">Tip</p>

    Создайте резервную копию файла `BitLocker-Recovery-Key.txt` с рабочего стола на отдельном устройстве хранения данных. Потеря этого кода восстановления может привести к потере данных.

</div>

</details>

### FileVault

<div class="admonition recommendation" markdown>

![Логотип FileVault](assets/img/encryption-software/filevault.png){ align=right }

**FileVault** - это решение для шифрования томов "на лету", встроенное в macOS. FileVault рекомендуется, поскольку он [использует](https://support.apple.com/guide/security/volume-encryption-with-filevault-sec4c6dc1b6e/web) аппаратные возможности безопасности, представленные в SoC процессорах Apple или чипе безопасности T2.

[:octicons-info-16:](https://support.apple.com/ru-ru/guide/mac-help/mh11785/mac){ .card-link title=Документация}

</details>

</div>

Мы рекомендуем хранить локальный ключ восстановления в надежном месте, а не использовать для восстановления учетную запись iCloud.

### Linux Unified Key Setup (LUKS)

<div class="admonition recommendation" markdown>

![Логотип LUKS](assets/img/encryption-software/luks.png){ align=right }

**LUKS** - это стандартный метод FDE для Linux. Его можно использовать для шифрования полных томов, разделов или создания зашифрованных контейнеров.

[:octicons-home-16: Homepage](https://gitlab.com/cryptsetup/cryptsetup/-/blob/main/README.md){ .md-button .md-button--primary }
[:octicons-info-16:](https://gitlab.com/cryptsetup/cryptsetup/-/wikis/home){ .card-link title=Documentation}
[:octicons-code-16:](https://gitlab.com/cryptsetup/cryptsetup){ .card-link title="Source Code" }

</details>

</div>

<details class="example" markdown>
<summary>Creating and opening encrypted containers</summary>

```bash
dd if=/dev/urandom of=/path-to-file bs=1M count=1024 status=progress
sudo cryptsetup luksFormat /path-to-file
```

#### Opening encrypted containers

We recommend opening containers and volumes with `udisksctl` as this uses [Polkit](https://en.wikipedia.org/wiki/Polkit). Большинство файловых менеджеров, например, входящих в состав популярных настольных сред, могут разблокировать зашифрованные файлы. Tools like [udiskie](https://github.com/coldfix/udiskie) can run in the system tray and provide a helpful user interface.

```bash
udisksctl loop-setup -f /path-to-file
udisksctl unlock -b /dev/loop0
```

</details>

<div class="admonition note" markdown>
<p class="admonition-title">Remember to back up volume headers</p>

Мы рекомендуем всегда [создавать резервные копии заголовков LUKS](https://wiki.archlinux.org/title/Dm-crypt/Device_encryption#Backup_and_restore) на случай частичного отказа диска. This can be done with:

```bash
cryptsetup luksHeaderBackup /dev/device --header-backup-file /mnt/backup/file.img
```

</div>

## Для командной строки

Инструменты с интерфейсом командной строки полезны для интеграции [shell scripts](https://en.wikipedia.org/wiki/Shell_script).

### Kryptor

<div class="admonition recommendation" markdown>

![Логотип Kryptor](assets/img/encryption-software/kryptor.png){ align=right }

**Kryptor** - это бесплатный инструмент для шифрования и подписи файлов с открытым исходным кодом, использующий современные и безопасные криптографические алгоритмы. It aims to be a better version of [age](https://github.com/FiloSottile/age) and [Minisign](https://jedisct1.github.io/minisign) to provide a simple, easier alternative to GPG.

[:octicons-home-16: Homepage](https://kryptor.co.uk){ .md-button .md-button--primary }
[:octicons-eye-16:](https://kryptor.co.uk/features#privacy){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://kryptor.co.uk/tutorial){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/samuel-lucas6/Kryptor){ .card-link title="Source Code" }
[:octicons-heart-16:](https://kryptor.co.uk/#donate){ .card-link title=Contribute }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-windows11: Windows](https://kryptor.co.uk)
- [:simple-apple: macOS](https://kryptor.co.uk)
- [:simple-linux: Linux](https://kryptor.co.uk)

</details>

</div>

### Tomb

<div class="admonition recommendation" markdown>

![Логотип Tomb](assets/img/encryption-software/tomb.png){ align=right }

**Tomb** - это оболочка командной строки для LUKS. It supports steganography via [third-party tools](https://dyne.org/software/tomb/#advanced-usage).

[:octicons-home-16: Homepage](https://dyne.org/software/tomb){ .md-button .md-button--primary }
[:octicons-info-16:](https://github.com/dyne/Tomb/wiki){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/dyne/Tomb){ .card-link title="Source Code" }
[:octicons-heart-16:](https://dyne.org/donate){ .card-link title=Contribute }

</details>

</div>

## OpenPGP

OpenPGP иногда необходим для решения специфических задач, таких как цифровая подпись и шифрование электронной почты. PGP имеет множество функций и является [комплексным](https://latacora.micro.blog/2019/07/16/the-pgp-problem.html), поскольку существует уже долгое время. Для таких задач, как подписание или шифрование файлов, мы предлагаем использовать вышеуказанные варианты.

При шифровании с помощью PGP у вас есть возможность настроить различные параметры в файле `gpg.conf`. We recommend staying with the standard options specified in the [GnuPG user FAQ](https://gnupg.org/faq/gnupg-faq.html#new_user_gpg_conf).

<div class="admonition tip" markdown>
<p class="admonition-title">Use future defaults when generating a key</p>

When [generating keys](https://gnupg.org/gph/en/manual/c14.html) we suggest using the `future-default` command as this will instruct GnuPG use modern cryptography such as [Curve25519](https://en.wikipedia.org/wiki/Curve25519#History) and [Ed25519](https://ed25519.cr.yp.to):

```bash
gpg --quick-gen-key alice@example.com future-default
```

</div>

### GNU Privacy Guard

<div class="admonition recommendation" markdown>

![Логотип GNU Privacy Guard](assets/img/encryption-software/gnupg.svg){ align=right }

**GnuPG** - это GPL-альтернатива криптографическому пакету PGP. GnuPG совместим с [RFC 4880](https://tools.ietf.org/html/rfc4880), который является текущей спецификацией IETF для OpenPGP. The GnuPG project has been working on an [updated draft](https://datatracker.ietf.org/doc/draft-ietf-openpgp-crypto-refresh) in an attempt to modernize OpenPGP. GnuPG является частью фонда свободного программного обеспечения GNU и получил крупное [финансирование](https://gnupg.org/blog/20220102-a-new-future-for-gnupg.html) от правительства Германии.

[:octicons-home-16: Homepage](https://gnupg.org){ .md-button .md-button--primary }
[:octicons-eye-16:](https://gnupg.org/privacy-policy.html){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://gnupg.org/documentation/index.html){ .card-link title=Documentation}
[:octicons-code-16:](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gnupg.git){ .card-link title="Source Code" }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=org.sufficientlysecure.keychain)
- [:simple-windows11: Windows](https://gpg4win.org/download.html)
- [:simple-apple: macOS](https://gpgtools.org)
- [:simple-linux: Linux](https://gnupg.org/download/index.html#binary)

</details>

</div>

### GPG4win

<div class="admonition recommendation" markdown>

![Логотип GPG4win](assets/img/encryption-software/gpg4win.svg){ align=right }

**GPG4win** - это пакет для Windows от [Intevation и g10 Code](https://gpg4win.org/impressum.html). Он включает в себя [различные инструменты](https://gpg4win.org/about.html), которые могут помочь вам в использовании GPG в Microsoft Windows. Проект был инициирован и первоначально [финансировался](https://web.archive.org/web/20190425125223/https://joinup.ec.europa.eu/news/government-used-cryptography) федеральным управлением по информационной безопасности Германии (BSI) в 2005 году.

[:octicons-home-16: Homepage](https://gpg4win.org){ .md-button .md-button--primary }
[:octicons-eye-16:](https://gpg4win.org/privacy-policy.html){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://gpg4win.org/documentation.html){ .card-link title=Documentation}
[:octicons-code-16:](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=summary){ .card-link title="Source Code" }
[:octicons-heart-16:](https://gpg4win.org/donate.html){ .card-link title=Contribute }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-windows11: Windows](https://gpg4win.org/download.html)

</details>

</div>

### GPG Suite

<div class="admonition note" markdown>
<p class="admonition-title">Note</p>

We suggest [Canary Mail](email-clients.md#canary-mail-ios) for using PGP with email on iOS devices.

</div>

<div class="admonition recommendation" markdown>

![GPG Suite logo](assets/img/encryption-software/gpgsuite.png){ align=right }

**GPG Suite** provides OpenPGP support for [Apple Mail](email-clients.md#apple-mail-macos) and macOS.

Мы рекомендуем ознакомиться с их [первыми шагами](https://gpgtools.tenderapp.com/kb/how-to/first-steps-where-do-i-start-where-do-i-begin-setup-gpgtools-create-a-new-key-your-first-encrypted-email) и [базой знаний](https://gpgtools.tenderapp.com/kb) для получения поддержки.

[:octicons-home-16: Homepage](https://gpgtools.org){ .md-button .md-button--primary }
[:octicons-eye-16:](https://gpgtools.org/privacy){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://gpgtools.tenderapp.com/kb){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/GPGTools){ .card-link title="Source Code" }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-apple: macOS](https://gpgtools.org)

</details>

</div>

### OpenKeychain

<div class="admonition recommendation" markdown>

![Логотип OpenKeychain](assets/img/encryption-software/openkeychain.svg){ align=right }

**OpenKeychain** - это Android-реализация GnuPG. It's commonly required by mail clients such as [K-9 Mail](email-clients.md#k-9-mail-android) and [FairEmail](email-clients.md#fairemail-android) and other Android apps to provide encryption support. Cure53 completed a [security audit](https://openkeychain.org/openkeychain-3-6) of OpenKeychain 3.6 in October 2015. Технические подробности об аудите и решениях OpenKeychain можно найти на сайте [здесь](https://github.com/open-keychain/open-keychain/wiki/cure53-Security-Audit-2015).

[:octicons-home-16: Homepage](https://openkeychain.org){ .md-button .md-button--primary }
[:octicons-eye-16:](https://openkeychain.org/help/privacy-policy){ .card-link title="Privacy Policy" }
[:octicons-info-16:](https://openkeychain.org/faq){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/open-keychain/open-keychain){ .card-link title="Source Code" }

<details class="downloads" markdown>
<summary>Downloads</summary>

- [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=org.sufficientlysecure.keychain)

</details>

</div>

## Критерии

**Обрати внимание, что у нас нет связей ни с одним проектом, который мы рекомендуем.** В дополнение к [нашим стандартным критериям](about/criteria.md) мы разработали четкий набор требований, позволяющий давать объективные рекомендации. Перед тем, как вы решите выбрать какой-либо проект, мы рекомендуем вам ознакомиться со списком критериев и провести собственное исследование, чтобы убедиться в правильности своего выбора.

### Минимальные требования

- Cross-platform encryption apps must be open source.
- Приложения для шифрования файлов должны поддерживать дешифрование на Linux, macOS и Windows.
- Приложения для шифрования внешних дисков должны поддерживать дешифрование в Linux, macOS и Windows.
- Приложения для шифрования всего диска должны быть кроссплатформенными или встроенными в операционную систему.

### В лучшем случае

Эти критерии представляют собой то, что мы хотели бы видеть от идеального проекта в этой категории. Наши рекомендации могут не соответствовать всем или нескольким из этих критериев, но проекты, которые им соответствуют, расположены выше остальных.

- Приложения для шифрования операционной системы (FDE) должны использовать аппаратную защиту, такую как TPM или Secure Enclave.
- Приложения для шифрования файлов должны иметь поддержку мобильных платформ.
