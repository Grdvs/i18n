---
meta_title: "Empfehlungen für verschlüsselte private E-Mail-Dienste - Privacy Guides"
title: "E-Mail Dienste"
icon: material/email
description: Diese E-Mail-Dienstleister speichern deine E-Mails sicher und viele davon bieten auch interoperable OpenPGP-Verschlüsselung mit anderen Anbietern.
cover: email.png
---

E-Mail ist praktisch eine Voraussetzung für die Nutzung aller Online-Dienste, wir empfehlen sie jedoch nicht zur Kommunikation von Mensch zu Mensch. Anstatt E-Mails für die Kontaktaufnahme mit anderen Personen zu verwenden, überleg ob du einen Instant Messenger benutzen kannst, der Forward Secrecy (auf Deutsch etwa "vorwärts gerichtete Geheimhaltung") unterstützt.

[Empfohlene Instant Messenger](real-time-communication.md ""){.md-button}

Für alles andere empfehlen wir eine Reihe von E-Mail-Anbietern, die auf nachhaltigen Geschäftsmodellen basieren und integrierte Sicherheits- und Datenschutzfunktionen bieten.

- [OpenPGP-kompatible E-Mail-Anbieter :material-arrow-right-drop-circle:](#openpgp-compatible-services)
- [Andere verschlüsselte Anbieter :material-arrow-right-drop-circle:](#more-providers)
- [E-Mail-Alias-Dienste :material-arrow-right-drop-circle:](#email-aliasing-services)
- [Selbstbetreibbare Optionen :material-arrow-right-drop-circle:](#self-hosting-email)

## OpenPGP-kompatible Dienste

Diese Anbieter unterstützen von Haus aus die OpenPGP-Ver- und Entschlüsselung und den Web Key Directory (WKD)-Standard, so dass anbieterunabhängige E2E-verschlüsselte E-Mails möglich sind. Zum Beispiel können Kunden von Proton Mail eine E2EE-Nachricht an Kunden von Mailbox.org senden oder sie können OpenPGP-verschlüsselte Benachrichtigungen von Internetdiensten erhalten, die dies unterstützen.

<div class="grid cards" markdown>

- ![Proton Mail logo](assets/img/email/protonmail.svg){ .twemoji } [Proton Mail](email.md#proton-mail)
- ![Mailbox.org logo](assets/img/email/mailboxorg.svg){ .twemoji } [Mailbox.org](email.md#mailboxorg)

</div>

!!! warning

    Bei der Verwendung von E2EE-Technologien wie OpenPGP enthalten E-Mails immer noch einige Metadaten in der Kopfzeile der E-Mail die nicht verschlüsselt sind. Mehr über [E-Mail Metadaten](basics/email-security.md#email-metadata-overview).
    
    OpenPGP unterstützt auch keine Perfect Forward Secrecy, d. h. wenn entweder dein eigener privater Schlüssel oder der deines Kommunikationspartners gestohlen wird, sind alle vorher damit verschlüsselten Nachrichten offengelegt. [Wie schütze ich meine privaten Schlüssel?](basics/email-security.md#how-do-i-protect-my-private-keys)

### Proton Mail

!!! recommendation

    ![Proton Mail logo](assets/img/email/protonmail.svg){ align=right }
    
    **Proton Mail** ist ein E-Mail-Dienst mit dem Schwerpunkt auf Datenschutz, Verschlüsselung, Sicherheit und Benutzerfreundlichkeit. Sie sind seit **2013** in Betrieb. Die Proton AG hat ihren Sitz in Genf, Schweiz. Konten im kostenlosen Tarif beginnen mit 1 GB Speicherplatz.
    
    [:octicons-home-16: Homepage](https://mullvad.net){ .md-button .md-button--primary }
    [:simple-torbrowser:](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion){ .card-link title="Onion Dienst" }
    [:octicons-eye-16:](https://proton.me/legal/privacy/){ .card-link title="Datenschutzrichtlinie" }
    [:octicons-info-16:](https://proton.me/support/mail/){ .card-link title=Dokumentation}
    [:octicons-code-16:](https://github.com/ProtonMail){ .card-link title="Quellcode" }
    
    ??? downloads
    
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=ch.protonmail.android)
        - [:simple-appstore: App Store](https://apps.apple.com/app/apple-store/id979659905)
        - [:simple-github: GitHub](https://github.com/ProtonMail/proton-mail-android/releases)
        - [:simple-windows11: Windows](https://proton.me/mail/bridge#download)
        - [:simple-apple: macOS](https://proton.me/mail/bridge#download)
        - [:simple-linux: Linux](https://proton.me/mail/bridge#download)
        - [:octicons-browser-16: Web](https://mail.proton.me)

Kostenlose Konten haben einige Einschränkungen, wie z. B. die fehlende Möglichkeit Text zu durchsuchen und keinen Zugang zu [Proton Mail Bridge](https://proton.me/mail/bridge). Diese ist für die Verwendung eines [empfohlenen Desktop-E-Mail-Programms](email-clients.md) (z. B. Thunderbird) erforderlich. Bezahlte Konten umfassen Funktionen wie Proton Mail Bridge, zusätzlichen Speicher und die Nutzung eigener Domains. Am 9. November 2021 wurden durch [Securitum](https://research.securitum.com) ein Sicherheitsaudit durchgeführt und  die Anwendungen von Proton Mail [zertifiziert](https://proton.me/blog/security-audit-all-proton-apps).

Wenn du den Proton Unlimited, Business oder Visionary Tarif nutzt, erhältst du zusätzlich [SimpleLogin](#simplelogin) Premium kostenlos dazu.

Proton Mail hat interne Absturzberichte, die sie **nicht** mit Dritten teilen. Die Absturzberichte können in den Einstellungen deaktiviert werden: **Einstellungen** > **Gehe zu Einstellungen** > **Konto** > **Sicherheit und Datenschutz** > **Absturzberichte senden**.

#### :material-check:{ .pg-green } Eigene Domains und Aliase

Nutzer eines kostenpflichtigen Proton Mail Tarifs können ihre eigene Domain oder eine [Catch-All](https://proton.me/support/catch-all) Adresse nutzen. Proton Mail unterstützt auch [Unteradressierung](https://proton.me/support/creating-aliases), dieses ist für Leute nützlich, die keine Domain kaufen möchten.

#### :material-check:{ .pg-green } Diskrete Zahlungsmöglichkeiten

Proton Mail akzeptiert, neben den üblichen Zahlungen per Kredit-/Debitkarte, [Bitcoin](advanced/payments.md#other-coins-bitcoin-ethereum-etc)und PayPal, auch [Bargeld per Post](https://proton.me/support/payment-options).

#### :material-check:{ .pg-green } Kontosicherheit

Proton Mail unterstützt TOTP [Zwei-Faktor-Authentifizierung](https://proton.me/de/support/two-factor-authentication-2fa) und [Hardware-Sicherheitsschlüssel](https://proton.me/de/support/2fa-security-key) unter Verwendung der Standards FIDO2 oder U2F. Für die Verwendung eines Hardwaresicherheitsschlüssels muss zunächst die TOTP-Zwei-Faktor-Authentifizierung eingerichtet werden.

#### :material-check:{ .pg-green } Datensicherheit

Proton Mail verfügt über [Zero-Access-Verschlüsselung](https://proton.me/de/blog/zero-access-encryption) bei Ablage auf dem Server für deine E-Mails und [Kalender](https://proton.me/de/blog/protoncalendar-security-model). Die mit einer Zero-Access-Verschlüsselung gesicherten Daten sind nur für dich zugänglich.

Bestimmte Informationen, die in [Proton Contacts](https://proton.me/support/proton-contacts) gespeichert sind, wie z. B. Anzeigenamen und E-Mail-Adressen, sind nicht mit einer Zero-Access-Verschlüsselung gesichert. Kontaktfelder, die eine Zero-Access-Verschlüsselung unterstützen, wie z. B. Telefonnummern, sind mit einem Vorhängeschloss-Symbol gekennzeichnet.

#### :material-check:{ .pg-green } E-Mail-Verschlüsselung

Proton Mail hat [die OpenPGP-Verschlüsselung](https://proton.me/support/how-to-use-pgp) in sein Webmail integriert. E-Mails an andere Proton Mail-Konten werden automatisch verschlüsselt. Die Verschlüsselung an Nicht-Proton Mail-Adressen mit einem OpenPGP-Schlüssel kannst du ganz einfach in deinen Kontoeinstellungen aktivieren. Es ist auch möglich, [Nachrichten an Nicht-Proton-Mail-Adressen](https://proton.me/de/support/password-protected-emails) zu verschlüsseln, ohne dass diese sich für ein Proton-Mail-Konto anmelden oder Software wie OpenPGP verwenden müssen.

Proton Mail unterstützt auch die Suche nach öffentlichen Schlüsseln über HTTP in ihrem [Web Key Directory (WKD)](https://wiki.gnupg.org/WKD). Dies ermöglicht es Personen, die Proton Mail nicht verwenden, die OpenPGP-Schlüssel von Proton Mail-Konten für anbieterübergreifende E2EE leicht zu finden.


#### :material-information-outline:{ .pg-blue } Kontokündigung

Wenn du ein kostenpflichtiges Konto hast und deine Rechnung [nach 14 Tagen noch nicht bezahlt ist](https://proton.me/de/support/delinquency), kannst du nicht mehr auf Ihre Daten zugreifen. Nach 30 Tagen wird dein Konto als säumig markiert und kann keine E-Mails mehr empfangen. Während dieses Zeitraums werden dir die Kosten weiterhin in Rechnung gestellt.

#### :material-information-outline:{ .pg-blue } Zusätzliche Funktionen

Proton Mail bietet einen "Unlimited"-Tarif für 9,99 €/Monat an, der zusätzlich zu mehreren Konten, Domains, Aliasen und 500 GB Speicherplatz auch den Zugang zu Proton VPN ermöglicht.

Proton Mail bietet keine Funktion für deinen digitalen Nachlass.

### Mailbox.org

!!! recommendation

    ![Mailbox.org-Logo](assets/img/email/mailboxorg.svg){ align=right }
    
    **Mailbox.org** ist ein E-Mail-Dienst, mit dem Ziel sicher und werbefrei zu sein und der mit 100 % erneuerbaren Energien betrieben wird. Er wird seit 2014 betrieben. Mailbox.org hat seinen Sitz in Berlin, Deutschland. Konten im günstigsten Tarif beginnen mit 2 GB Speicherplatz, der je nach Bedarf erweitert werden kann.
    
    [:octicons-home-16: Homepage](https://mailbox.org){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://mailbox.org/de/datenschutz){ .card-link title="Datenschutzhinweise" }
    [:octicons-info-16:](https://kb.mailbox.org/de/privat){ .card-link title=Dokumentation}
    
    ??? downloads
    
        - [:octicons-browser-16: Web](https://login.mailbox.org)

#### :material-check:{ .pg-green } Eigene Domains und Aliase

Bei Mailbox.org kannst du deine eigene Domain verwenden, und sie unterstützen [Catch-All](https://kb.mailbox.org/de/privat/e-mail-mit-eigener-domain/eine-eigene-domain-mit-catch-all-benutzen) Adressen. Mailbox.org unterstützt auch die [Subadressierung/Aliasse](https://kb.mailbox.org/de/privat/e-mail-artikel/was-sind-aliasse-und-wie-nutze-ich-sie), was hilfreich ist, wenn du keine Domain kaufen möchtest.

#### :material-check:{ .pg-green } Diskrete Zahlungsmöglichkeiten

Mailbox.org akzeptiert keine Kryptowährungen, da deren Zahlungsanbieter BitPay seinen Betrieb in Deutschland eingestellt hat. Sie akzeptieren jedoch Bargeld per Post, Barzahlung auf ein Bankkonto, Banküberweisung, Kreditkarte, PayPal und einige Deutschland spezifische Anbieter: paydirekt und Sofortüberweisung.

#### :material-check:{ .pg-green } Kontosicherheit

Mailbox.org unterstützt [Zwei-Faktor-Authentifizierung](https://kb.mailbox.org/de/privat/sicherheit-privatsphaere-artikel/die-zwei-faktor-authentifizierung-einrichten) nur für Webmail. Du kannst entweder TOTP oder einen [YubiKey](https://de.wikipedia.org/wiki/Yubikey) über die [YubiCloud](https://www.yubico.com/products/services-software/yubicloud)verwenden. Webstandards wie [WebAuthn](https://de.wikipedia.org/wiki/WebAuthn) werden noch nicht unterstützt.

#### :material-information-outline:{ .pg-blue } Datensicherheit

Mailbox.org ermöglicht die Verschlüsselung eingehender E-Mails mit ihrem [verschlüsselten Postfach](https://kb.mailbox.org/display/MBOKBEN/The+Encrypted+Mailbox). Neue eingehende Nachrichten werden dann sofort mit deinem öffentlichen Schlüssel verschlüsselt.

Allerdings unterstützt [Open-Exchange](https://de.wikipedia.org/wiki/Open-Xchange), die von Mailbox.org verwendete Softwareplattform, [nicht](https://kb.mailbox.org/de/business/sicherheit-privatsphaere-artikel/sind-kalender-und-adressbuch-verschluesselt) die Verschlüsselung deines Adressbuchs und Kalenders. Eine [eigenständige Lösung](calendar.md) könnte für diese Informationen besser geeignet sein.

#### :material-check:{ .pg-green } E-Mail-Verschlüsselung

Mailbox.org hat [eine Verschlüsselung](https://kb.mailbox.org/de/privat/verschluesselung-mit-mailbox-org-guard/verschluesselte-nachrichten-versenden) in ihr Webmail integriert, die den Versand von Nachrichten an Personen mit öffentlichen OpenPGP-Schlüsseln vereinfacht. Sie ermöglichen auch [Empfängern, die kein Mailbox.org Konto besitzen, eine E-Mail auf den Servern von Mailbox.org zu entschlüsseln](https://kb.mailbox.org/de/privat/verschluesselung-mit-mailbox-org-guard/verschluesselte-nachrichten-versenden#VerschluesselteNachrichtenversenden-Waspassiert,wennderEmpf%C3%A4ngerkeinPGPnutzt?). Diese Funktion ist nützlich, wenn der Empfänger OpenPGP nicht nutzt und daher eine Kopie der E-Mail in seinem eigenen Postfach nicht entschlüsseln kann.

Mailbox.org unterstützt auch die Suche nach öffentlichen Schlüsseln über HTTP von ihrem [Web Key Directory (WKD)](https://wiki.gnupg.org/WKD). Dies ermöglicht es Personen, die Mailbox.org nicht verwenden, die OpenPGP-Schlüssel von Mailbox.org-Konten für anbieterübergreifende E2EE leicht zu finden.

#### :material-information-outline:{ .pg-blue } Kontokündigung

Ihr Konto wird bei Vertragsende auf ein eingeschränktes Benutzerkonto umgestellt, nach [30 Tagen wird es unwiderruflich gelöscht](https://kb.mailbox.org/de/privat/ihr-account-bei-mailbox-org/mailbox-org-bezahlen#mailbox.orgbezahlen-MeineVertragslaufzeitistabgelaufen-wasjetzt?).

#### :material-information-outline:{ .pg-blue } Zusätzliche Funktionen

Du kannst auf dein Mailbox.org-Konto über IMAP/SMTP zugreifen, indem du den [.onion-Dienst](https://kb.mailbox.org/de/privat/sicherheit-privatsphaere-artikel/den-tor-exit-node-von-mailbox-org-verwenden) nutzt. Auf die Webmail-Schnittstelle kann jedoch nicht über den .onion-Dienst zugegriffen werden und es können TLS-Zertifikatsfehler auftreten.

All accounts come with limited cloud storage that [can be encrypted](https://kb.mailbox.org/display/MBOKBEN/Encrypt+files+on+your+Drive). Mailbox.org also offers the alias [@secure.mailbox.org](https://kb.mailbox.org/display/MBOKBEN/Ensuring+E-Mails+are+Sent+Securely), which enforces the TLS encryption on the connection between mail servers, otherwise the message will not be sent at all. Mailbox.org also supports [Exchange ActiveSync](https://en.wikipedia.org/wiki/Exchange_ActiveSync) in addition to standard access protocols like IMAP and POP3.

Mailbox.org has a digital legacy feature for all plans. You can choose whether you want any of your data to be passed to heirs providing that they apply and provide your testament. Alternatively, you can nominate a person by name and address.

## More Providers

These providers store your emails with zero-knowledge encryption, making them great options for keeping your stored emails secure. However, they don't support interoperable encryption standards for E2EE communications between providers.

<div class="grid cards" markdown>

- ![StartMail logo](assets/img/email/startmail.svg#only-light){ .twemoji }![StartMail logo](assets/img/email/startmail-dark.svg#only-dark){ .twemoji } [StartMail](email.md#startmail)
- ![Tutanota logo](assets/img/email/tutanota.svg){ .twemoji } [Tutanota](email.md#tutanota)

</div>

### StartMail

!!! recommendation

    ![StartMail logo](assets/img/email/startmail.svg#only-light){ align=right }
    ![StartMail logo](assets/img/email/startmail-dark.svg#only-dark){ align=right }
    
    **StartMail** is an email service with a focus on security and privacy through the use of standard OpenPGP encryption. StartMail has been in operation since 2014 and is based in Boulevard 11, Zeist Netherlands. Accounts start with 10GB. They offer a 30-day trial.
    
    [:octicons-home-16: Homepage](https://www.startmail.com/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://www.startmail.com/en/privacy/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://support.startmail.com){ .card-link title=Documentation}
    
    ??? downloads
    
        - [:octicons-browser-16: Web](https://mail.startmail.com/login)

#### :material-check:{ .pg-green } Eigene Domains und Aliase

Personal accounts can use [Custom or Quick](https://support.startmail.com/hc/en-us/articles/360007297457-Aliases) aliases. [Custom domains](https://support.startmail.com/hc/en-us/articles/4403911432209-Setup-a-custom-domain) are also available.

#### :material-alert-outline:{ .pg-orange } Private Payment Methods

StartMail accepts Visa, MasterCard, American Express and Paypal. StartMail also has other [payment options](https://support.startmail.com/hc/en-us/articles/360006620637-Payment-methods) such as [Bitcoin](advanced/payments.md#other-coins-bitcoin-ethereum-etc) (currently only for Personal accounts) and SEPA Direct Debit for accounts older than a year.

#### :material-check:{ .pg-green } Kontosicherheit

StartMail supports TOTP two factor authentication [for webmail only](https://support.startmail.com/hc/en-us/articles/360006682158-Two-factor-authentication-2FA). They do not allow U2F security key authentication.

#### :material-information-outline:{ .pg-blue } Datensicherheit

StartMail has [zero access encryption at rest](https://www.startmail.com/en/whitepaper/#_Toc458527835), using their "user vault" system. When you log in, the vault is opened, and the email is then moved to the vault out of the queue where it is decrypted by the corresponding private key.

StartMail supports importing [contacts](https://support.startmail.com/hc/en-us/articles/360006495557-Import-contacts) however, they are only accessible in the webmail and not through protocols such as [CalDAV](https://en.wikipedia.org/wiki/CalDAV). Contacts are also not stored using zero knowledge encryption.

#### :material-check:{ .pg-green } E-Mail-Verschlüsselung

StartMail has [integrated encryption](https://support.startmail.com/hc/en-us/sections/360001889078-Encryption) in their webmail, which simplifies sending encrypted messages with public OpenPGP keys. However, they do not support the Web Key Directory standard, making the discovery of a Startmail mailbox's public key more challenging for other email providers or clients.

#### :material-information-outline:{ .pg-blue } Kontokündigung

On account expiration, StartMail will permanently delete your account after [6 months in 3 phases](https://support.startmail.com/hc/en-us/articles/360006794398-Account-expiration).

#### :material-information-outline:{ .pg-blue } Additional Functionality

StartMail allows for proxying of images within emails. If you allow the remote image to be loaded, the sender won't know what your IP address is.

StartMail does not offer a digital legacy feature.

### Tutanota

!!! recommendation

    ![Tutanota logo](assets/img/email/tutanota.svg){ align=right }
    
    **Tutanota** is an email service with a focus on security and privacy through the use of encryption. Tutanota has been in operation since **2011** and is based in Hanover, Germany. Accounts start with 1GB storage with their free plan.
    
    [:octicons-home-16: Homepage](https://tutanota.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://tutanota.com/privacy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://tutanota.com/faq){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/tutao/tutanota){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://tutanota.com/community/){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=de.tutao.tutanota)
        - [:simple-appstore: App Store](https://apps.apple.com/app/tutanota/id922429609)
        - [:simple-github: GitHub](https://github.com/tutao/tutanota/releases)
        - [:simple-windows11: Windows](https://tutanota.com/#download)
        - [:simple-apple: macOS](https://tutanota.com/#download)
        - [:simple-linux: Linux](https://tutanota.com/#download)
        - [:octicons-browser-16: Web](https://mail.tutanota.com/)

Tutanota doesn't support the [IMAP protocol](https://tutanota.com/faq/#imap) or the use of third-party [email clients](email-clients.md), and you also won't be able to add [external email accounts](https://github.com/tutao/tutanota/issues/544#issuecomment-670473647) to the Tutanota app. Neither [Email import](https://github.com/tutao/tutanota/issues/630) or [subfolders](https://github.com/tutao/tutanota/issues/927) are currently supported, though this is [due to be changed](https://tutanota.com/blog/posts/kickoff-import). Emails can be exported [individually or by bulk selection](https://tutanota.com/howto#generalMail) per folder, which may be inconvenient if you have many folders.

#### :material-check:{ .pg-green } Eigene Domains und Aliase

Paid Tutanota accounts can use up to 5 [aliases](https://tutanota.com/faq#alias) and [custom domains](https://tutanota.com/faq#custom-domain). Tutanota doesn't allow for [subaddressing (plus addresses)](https://tutanota.com/faq#plus), but you can use a [catch-all](https://tutanota.com/howto#settings-global) with a custom domain.

#### :material-information-outline:{ .pg-blue } Private Payment Methods

Tutanota only directly accepts credit cards and PayPal, however [cryptocurrency](cryptocurrency.md) can be used to purchase gift cards via their [partnership](https://tutanota.com/faq/#cryptocurrency) with Proxystore.

#### :material-check:{ .pg-green } Kontosicherheit

Tutanota supports [two factor authentication](https://tutanota.com/faq#2fa) with either TOTP or U2F.

#### :material-check:{ .pg-green } Datensicherheit

Tutanota has [zero access encryption at rest](https://tutanota.com/faq#what-encrypted) for your emails, [address book contacts](https://tutanota.com/faq#encrypted-address-book), and [calendars](https://tutanota.com/faq#calendar). This means the messages and other data stored in your account are only readable by you.

#### :material-information-outline:{ .pg-blue } Email Encryption

Tutanota [does not use OpenPGP](https://www.tutanota.com/faq/#pgp). Tutanota accounts can only receive encrypted emails from non-Tutanota email accounts when sent via a [temporary Tutanota mailbox](https://www.tutanota.com/howto/#encrypted-email-external).

#### :material-information-outline:{ .pg-blue } Kontokündigung

Tutanota will [delete inactive free accounts](https://tutanota.com/faq#inactive-accounts) after six months. You can reuse a deactivated free account if you pay.

#### :material-information-outline:{ .pg-blue } Additional Functionality

Tutanota offers the business version of [Tutanota to non-profit organizations](https://tutanota.com/blog/posts/secure-email-for-non-profit) for free or with a heavy discount.

Tutanota also has a business feature called [Secure Connect](https://tutanota.com/secure-connect/). This ensures customer contact to the business uses E2EE. The feature costs €240/y.

Tutanota doesn't offer a digital legacy feature.

## Email Aliasing Services

An email aliasing service allows you to easily generate a new email address for every website you register for. The email aliases you generate are then forwarded to an email address of your choosing, hiding both your "main" email address and the identity of your email provider. True email aliasing is better than plus addressing commonly used and supported by many providers, which allows you to create aliases like yourname+[anythinghere]@example.com, because websites, advertisers, and tracking networks can trivially remove anything after the + sign to know your true email address.

<div class="grid cards" markdown>

- ![AnonAddy logo](assets/img/email/anonaddy.svg#only-light){ .twemoji }![AnonAddy logo](assets/img/email/anonaddy-dark.svg#only-dark){ .twemoji } [AnonAddy](email.md#anonaddy)
- ![SimpleLogin logo](assets/img/email/simplelogin.svg){ .twemoji } [SimpleLogin](email.md#simplelogin)

</div>

Email aliasing can act as a safeguard in case your email provider ever ceases operation. In that scenario, you can easily re-route your aliases to a new email address. In turn, however, you are placing trust in the aliasing service to continue functioning.

Using a dedicated email aliasing service also has a number of benefits over a catch-all alias on a custom domain:

- Aliases can be turned on and off individually when you need them, preventing websites from emailing you randomly.
- Replies are sent from the alias address, shielding your real email address.

They also have a number of benefits over "temporary email" services:

- Aliases are permanent and can be turned on again if you need to receive something like a password reset.
- Emails are sent to your trusted mailbox rather than stored by the alias provider.
- Temporary email services typically have public mailboxes which can be accessed by anyone who knows the address, aliases are private to you.

Our email aliasing recommendations are providers that allow you to create aliases on domains they control, as well as your own custom domain(s) for a modest yearly fee. They can also be self-hosted if you want maximum control. However, using a custom domain can have privacy-related drawbacks: If you are the only person using your custom domain, your actions can be easily tracked across websites simply by looking at the domain name in the email address and ignoring everything before the at (@) sign.

Using an aliasing service requires trusting both your email provider and your aliasing provider with your unencrypted messages. Some providers mitigate this slightly with automatic PGP encryption, which reduces the number of parties you need to trust from two to one by encrypting incoming emails before they are delivered to your final mailbox provider.

### AnonAddy

!!! recommendation

    ![AnonAddy logo](assets/img/email/anonaddy.svg#only-light){ align=right }
    ![AnonAddy logo](assets/img/email/anonaddy-dark.svg#only-dark){ align=right }
    
    **AnonAddy** lets you create 20 domain aliases on a shared domain for free, or unlimited "standard" aliases which are less anonymous.
    
    [:octicons-home-16: Homepage](https://anonaddy.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://anonaddy.com/privacy/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://app.anonaddy.com/docs/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/anonaddy){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://anonaddy.com/donate/){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-android: Android](https://anonaddy.com/faq/#is-there-an-android-app)
        - [:material-apple-ios: iOS](https://anonaddy.com/faq/#is-there-an-ios-app)
        - [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/en-GB/firefox/addon/anonaddy/)
        - [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/anonaddy-anonymous-email/iadbdpnoknmbdeolbapdackdcogdmjpe)

The number of shared aliases (which end in a shared domain like @anonaddy.me) that you can create is limited to 20 on AnonAddy's free plan and 50 on their $12/year plan. You can create unlimited standard aliases (which end in a domain like @[username].anonaddy.com or a custom domain on paid plans), however, as previously mentioned, this can be detrimental to privacy because people can trivially tie your standard aliases together based on the domain name alone. Unlimited shared aliases are available for $36/year.

Notable free features:

- [x] 20 Shared Aliases
- [x] Unlimited Standard Aliases
- [ ] No Outgoing Replies
- [x] 2 Recipient Mailboxes
- [x] Automatic PGP Encryption

### SimpleLogin

!!! recommendation

    ![Simplelogin logo](assets/img/email/simplelogin.svg){ align=right }
    
    **SimpleLogin** is a free service which provides email aliases on a variety of shared domain names, and optionally provides paid features like unlimited aliases and custom domains.
    
    [:octicons-home-16: Homepage](https://simplelogin.io){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://simplelogin.io/privacy/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://simplelogin.io/docs/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/simple-login){ .card-link title="Source Code" }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=io.simplelogin.android)
        - [:simple-appstore: App Store](https://apps.apple.com/app/id1494359858)
        - [:simple-github: GitHub](https://github.com/simple-login/Simple-Login-Android/releases)
        - [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/en-US/firefox/addon/simplelogin/)
        - [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/dphilobhebphkdjbpfohgikllaljmgbn)
        - [:simple-microsoftedge: Edge](https://microsoftedge.microsoft.com/addons/detail/simpleloginreceive-sen/diacfpipniklenphgljfkmhinphjlfff)
        - [:simple-safari: Safari](https://apps.apple.com/app/id1494051017)

SimpleLogin was [acquired by Proton AG](https://proton.me/news/proton-and-simplelogin-join-forces) as of April 8, 2022. If you use Proton Mail for your primary mailbox, SimpleLogin is a great choice. As both products are now owned by the same company you now only have to trust a single entity. We also expect that SimpleLogin will be more tightly integrated with Proton's offerings in the future. SimpleLogin continues to support forwarding to any email provider of your choosing. Securitum [audited](https://simplelogin.io/blog/security-audit/) SimpleLogin in early 2022 and all issues [were addressed](https://simplelogin.io/audit2022/web.pdf).

You can link your SimpleLogin account in the settings with your Proton account. If you have the Proton Unlimited, Business, or Visionary Plan, you will have SimpleLogin Premium for free.

Notable free features:

- [x] 10 Shared Aliases
- [x] Unlimited Replies
- [x] 1 Recipient Mailbox

## Self-Hosting Email

Advanced system administrators may consider setting up their own email server. Mail servers require attention and continuous maintenance in order to keep things secure and mail delivery reliable.

### Combined software solutions

!!! recommendation

    ![Mailcow logo](assets/img/email/mailcow.svg){ align=right }
    
    **Mailcow** is a more advanced mail server perfect for those with a bit more Linux experience. It has everything you need in a Docker container: A mail server with DKIM support, antivirus and spam monitoring, webmail and ActiveSync with SOGo, and web-based administration with 2FA support.
    
    [:octicons-home-16: Homepage](https://mailcow.email){ .md-button .md-button--primary }
    [:octicons-info-16:](https://mailcow.github.io/mailcow-dockerized-docs/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/mailcow/mailcow-dockerized){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://www.servercow.de/mailcow?lang=en#sal){ .card-link title=Contribute }

!!! recommendation

    ![Mail-in-a-Box logo](assets/img/email/mail-in-a-box.svg){ align=right }
    
    **Mail-in-a-Box** is an automated setup script for deploying a mail server on Ubuntu. Its goal is to make it easier for people to set up their own mail server.
    
    [:octicons-home-16: Homepage](https://mailinabox.email){ .md-button .md-button--primary }
    [:octicons-info-16:](https://mailinabox.email/guide.html){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/mail-in-a-box/mailinabox){ .card-link title="Source Code" }

For a more manual approach we've picked out these two articles:

- [Setting up a mail server with OpenSMTPD, Dovecot and Rspamd](https://poolp.org/posts/2019-09-14/setting-up-a-mail-server-with-opensmtpd-dovecot-and-rspamd/) (2019)
- [How To Run Your Own Mail Server](https://www.c0ffee.net/blog/mail-server-guide/) (August 2017)

## Criteria

**Please note we are not affiliated with any of the providers we recommend.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements for any Email provider wishing to be recommended, including implementing industry best practices, modern technology and more. We suggest you familiarize yourself with this list before choosing an Email provider, and conduct your own research to ensure the Email provider you choose is the right choice for you.

### Technologie

We regard these features as important in order to provide a safe and optimal service. You should consider whether the provider which has the features you require.

**Mindestvoraussetzung um zu qualifizieren:**

- Encrypts email account data at rest with zero-access encryption.
- Export capability as [Mbox](https://en.wikipedia.org/wiki/Mbox) or individual .eml with [RFC5322](https://datatracker.ietf.org/doc/rfc5322/) standard.
- Allow users to use their own [domain name](https://en.wikipedia.org/wiki/Domain_name). Custom domain names are important to users because it allows them to maintain their agency from the service, should it turn bad or be acquired by another company which doesn't prioritize privacy.
- Operates on owned infrastructure, i.e. not built upon third-party email service providers.

**Best Case:**

- Encrypts all account data (Contacts, Calendars, etc.) at rest with zero-access encryption.
- Integrated webmail E2EE/PGP encryption provided as a convenience.
- Support for [WKD](https://wiki.gnupg.org/WKD) to allow improved discovery of public OpenPGP keys via HTTP. GnuPG users can get a key by typing: `gpg --locate-key example_user@example.com`
- Support for a temporary mailbox for external users. This is useful when you want to send an encrypted email, without sending an actual copy to your recipient. These emails usually have a limited lifespan and then are automatically deleted. They also don't require the recipient to configure any cryptography like OpenPGP.
- Availability of the email provider's services via an [onion service](https://en.wikipedia.org/wiki/.onion).
- [Subaddressing](https://en.wikipedia.org/wiki/Email_address#Subaddressing) support.
- Catch-all or alias functionality for those who own their own domains.
- Use of standard email access protocols such as IMAP, SMTP or [JMAP](https://en.wikipedia.org/wiki/JSON_Meta_Application_Protocol). Standard access protocols ensure customers can easily download all of their email, should they want to switch to another provider.

### Datenschutz

Wir ziehen es vor, dass die von uns empfohlenen Anbieter*innen so wenig Daten wie möglich sammeln.

**Mindestvoraussetzung um zu qualifizieren:**

- Protect sender's IP address. Filter it from showing in the `Received` header field.
- Don't require personally identifiable information (PII) besides a username and a password.
- Privacy policy that meets the requirements defined by the GDPR
- Must not be hosted in the US due to [ECPA](https://en.wikipedia.org/wiki/Electronic_Communications_Privacy_Act#Criticism) which has [yet to be reformed](https://epic.org/ecpa/).

**Best Case:**

- Accepts [anonymous payment options](advanced/payments.md) ([cryptocurrency](cryptocurrency.md), cash, gift cards, etc.)

### Sicherheit

Email servers deal with a lot of very sensitive data. We expect that providers will adopt best industry practices in order to protect their members.

**Mindestvoraussetzung um zu qualifizieren:**

- Protection of webmail with 2FA, such as TOTP.
- Zero access encryption, builds on encryption at rest. The provider does not have the decryption keys to the data they hold. This prevents a rogue employee leaking data they have access to or remote adversary from releasing data they have stolen by gaining unauthorized access to the server.
- [DNSSEC](https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions) support.
- No TLS errors or vulnerabilities when being profiled by tools such as [Hardenize](https://www.hardenize.com/), [testssl.sh](https://testssl.sh/), or [Qualys SSL Labs](https://www.ssllabs.com/ssltest); this includes certificate related errors and weak DH parameters, such as those that led to [Logjam](https://en.wikipedia.org/wiki/Logjam_(computer_security)).
- A server suite preference (optional on TLSv1.3) for strong cipher suites which support forward secrecy and authenticated encryption.
- A valid [MTA-STS](https://tools.ietf.org/html/rfc8461) and [TLS-RPT](https://tools.ietf.org/html/rfc8460) policy.
- Valid [DANE](https://en.wikipedia.org/wiki/DNS-based_Authentication_of_Named_Entities) records.
- Valid [SPF](https://en.wikipedia.org/wiki/Sender_Policy_Framework) and [DKIM](https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail) records.
- Have a proper [DMARC](https://en.wikipedia.org/wiki/DMARC) record and policy or use [ARC](https://en.wikipedia.org/wiki/Authenticated_Received_Chain) for authentication. If DMARC authentication is being used, the policy must be set to `reject` or `quarantine`.
- A server suite preference of TLS 1.2 or later and a plan for [RFC8996](https://datatracker.ietf.org/doc/rfc8996/).
- [SMTPS](https://en.wikipedia.org/wiki/SMTPS) submission, assuming SMTP is used.
- Website security standards such as:
    - [HTTP Strict Transport Security](https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security)
    - [Subresource Integrity](https://en.wikipedia.org/wiki/Subresource_Integrity) if loading things from external domains.
- Must support viewing of [Message headers](https://en.wikipedia.org/wiki/Email#Message_header), as it is a crucial forensic feature to determine if an email is a phishing attempt.

**Best Case:**

- Support for hardware authentication, i.e. U2F and [WebAuthn](https://en.wikipedia.org/wiki/WebAuthn). U2F and WebAuthn are more secure as they use a private key stored on a client-side hardware device to authenticate people, as opposed to a shared secret that is stored on the web server and on the client side when using TOTP. Furthermore, U2F and WebAuthn are more resistant to phishing as their authentication response is based on the authenticated [domain name](https://en.wikipedia.org/wiki/Domain_name).
- [DNS Certification Authority Authorization (CAA) Resource Record](https://tools.ietf.org/html/rfc6844) in addition to DANE support.
- Implementation of [Authenticated Received Chain (ARC)](https://en.wikipedia.org/wiki/Authenticated_Received_Chain), this is useful for people who post to mailing lists [RFC8617](https://tools.ietf.org/html/rfc8617).
- Bug-bounty programs and/or a coordinated vulnerability-disclosure process.
- Website security standards such as:
    - [Content Security Policy (CSP)](https://en.wikipedia.org/wiki/Content_Security_Policy)
    - [RFC9163 Expect-CT](https://datatracker.ietf.org/doc/rfc9163/)

### Vertrauen

You wouldn't trust your finances to someone with a fake identity, so why trust them with your email? We require our recommended providers to be public about their ownership or leadership. We also would like to see frequent transparency reports, especially in regard to how government requests are handled.

**Mindestvoraussetzung um zu qualifizieren:**

- Public-facing leadership or ownership.

**Best Case:**

- Public-facing leadership.
- Frequent transparency reports.

### Marketing

With the email providers we recommend we like to see responsible marketing.

**Mindestvoraussetzung um zu qualifizieren:**

- Must self-host analytics (no Google Analytics, Adobe Analytics, etc.). The provider's site must also comply with [DNT (Do Not Track)](https://en.wikipedia.org/wiki/Do_Not_Track) for those who wish to opt-out.

Must not have any marketing which is irresponsible:

- Claims of "unbreakable encryption." Encryption should be used with the intention that it may not be secret in the future when the technology exists to crack it.
- Making guarantees of protecting anonymity 100%. When someone makes a claim that something is 100% it means there is no certainty for failure. We know people can quite easily deanonymize themselves in a number of ways, e.g.:

- Reusing personal information e.g. (email accounts, unique pseudonyms, etc.) that they accessed without anonymity software (Tor, VPN, etc.)
- [Browser fingerprinting](https://en.wikipedia.org/wiki/Device_fingerprint#Browser_fingerprint)

**Best Case:**

- Clear and easy to read documentation. This includes things like, setting up 2FA, email clients, OpenPGP, etc.

### Zusätzliche Funktionalitäten

While not strictly requirements, there are some other convenience or privacy factors we looked into when determining which providers to recommend.