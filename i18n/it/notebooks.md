---
title: "Appunti"
icon: material/notebook-edit-outline
description: Queste app criptate per prendere appunti consentono di tenere traccia dei propri appunti senza darli a terze parti.
cover: notebooks.png
---

Tieni traccia delle tue note e diari senza doverli dare a una terza parte.

Se stai attualmente utilizzando un'applicazione come Evernote, Google Keep o Microsoft OneNote, ti suggeriamo di scegliere una delle seguenti alernative che supportano E2EE.

## Cloud

### Joplin

!!! recommendation

    ![Logo Joplin](assets/img/notebooks/joplin.svg){ align=right }
    
    **Joplin** è un'applicazione gratuita, open-source e dotata di tutte le funzionalità per prendere appunti e per le attività da svolgere, in grado di gestire un gran numero di note markdown organizzate in taccuini e tag. Offre E2EE e può sincronizzarsi con Nextcloud, Dropbox e altro ancora. Offre anche la possibilità di importare facilmente note da Evernote e note in testo semplice.
    
    [:octicons-home-16: Pagina principale](https://joplinapp.org/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://joplinapp.org/privacy/){ .card-link title="Informativa sulla privacy" }
    [:octicons-info-16:](https://joplinapp.org/help/){ .card-link title=Documentazione}
    [:octicons-code-16:](https://github.com/laurent22/joplin){ .card-link title="Codice sorgente" }
    [:octicons-heart-16:](https://joplinapp.org/donate/){ .card-link title=Contribuisci }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=net.cozic.joplin)
        - [:simple-appstore: App Store](https://apps.apple.com/us/app/joplin/id1315599797)
        - [:simple-github: GitHub](https://github.com/laurent22/joplin-android/releases)
        - [:simple-windows11: Windows](https://joplinapp.org/#desktop-applications)
        - [:simple-apple: macOS](https://joplinapp.org/#desktop-applications)
        - [:simple-linux: Linux](https://joplinapp.org/#desktop-applications)
        - [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/firefox/addon/joplin-web-clipper/)
        - [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/joplin-web-clipper/alofnhikmmkdbbbgpnglcpdollgjjfek)

Joplin non supporta la protezione con password/PIN per [l'applicazione stessa o per i singoli appunti e taccuini](https://github.com/laurent22/joplin/issues/289). Tuttavia, i dati vengono comunque crittografati durante il transito e nella posizione di sincronizzazione utilizzando la chiave master. Da Gennaio 2023, Joplin supporta il blocco biometrico dell'app per [Android](https://joplinapp.org/changelog_android/#android-v2-10-3-https-github-com-laurent22-joplin-releases-tag-android-v2-10-3-pre-release-2023-01-05t11-29-06z) e [iOS](https://joplinapp.org/changelog_ios/#ios-v12-10-2-https-github-com-laurent22-joplin-releases-tag-ios-v12-10-2-2023-01-20t17-41-13z).

### Standard Notes

!!! recommendation

    ![Logo Standard Notes](assets/img/notebooks/standard-notes.svg){ align=right }
    
    **Standard Notes** è un'applicazione per appunti semplice e privata che rende i tuoi appunti facili e disponibili ovunque tu sia. È dotato di E2EE su ogni piattaforma e di una potente esperienza desktop con temi ed editor personalizzati. È stato anche [sottoposto a ispezione indipendente (PDF)](https://s3.amazonaws.com/standard-notes/security/Report-SN-Audit.pdf).
    
    [:octicons-home-16: Pagina principale](https://standardnotes.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://standardnotes.com/privacy){ .card-link title="Informativa sulla privacy" }
    [:octicons-info-16:](https://standardnotes.com/help){ .card-link title=Documentazione}
    [:octicons-code-16:](https://github.com/standardnotes){ .card-link title="Codice sorgente" }
    [:octicons-heart-16:](https://standardnotes.com/donate){ .card-link title=Contribuisci }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=com.standardnotes)
        - [:simple-appstore: App Store](https://apps.apple.com/app/id1285392450)
        - [:simple-github: GitHub](https://github.com/standardnotes/app/releases)
        - [:simple-windows11: Windows](https://standardnotes.com)
        - [:simple-apple: macOS](https://standardnotes.com)
        - [:simple-linux: Linux](https://standardnotes.com)
        - [:octicons-globe-16: Web](https://app.standardnotes.com/)

### Org-mode

!!! recommendation

    ![Logo Org-mode](assets/img/notebooks/org-mode.svg){ align=right }
    
    **Org-mode** è una [major mode](https://www.gnu.org/software/emacs/manual/html_node/elisp/Major-Modes.html) per GNU Emacs. Org-mode serve per prendere appunti, mantenere elenchi TODO, pianificare progetti e scrivere documenti con un sistema di testo semplice rapido ed efficace.
    
    La sincronizzazione è possibile con gli strumenti di [sincronizzazione dei file](file-sharing.md#file-sync). [:octicons-home-16: Pagina principale](https://orgmode.org){ .md-button .md-button--primary }
    [:octicons-info-16:](https://orgmode.org/manuals.html){ .card-link title=Documentazione}
    [:octicons-code-16:](https://git.savannah.gnu.org/cgit/emacs/org-mode.git){ .card-link title="Codice sorgente" }
    [:octicons-heart-16:](https://liberapay.com/bzg){ .card-link title=Contribuisci }

Cryptee offre 100 MB di spazio di archiviazione gratuito, con opzioni a pagamento se hai bisogno di più spazio. L'iscrizione non richiede l'email o altre informazioni d'identificazione personale.

## Note locali

### Org-mode

!!! recommendation

    ![Logo Org-mode](assets/img/notebooks/org-mode.svg){ align=right }
    
    **Org-mode** è una [modalità principale](https://www.gnu.org/software/emacs/manual/html_node/elisp/Major-Modes.html) per GNU Emacs. Org-mode serve per prendere appunti, gestire elenchi di cose da fare, pianificare progetti e scrivere documenti con un sistema di testo semplice rapido ed efficace. La sincronizzazione è possibile con gli strumenti di [sincronizzazione dei file](file-sharing.md#file-sync).
    
    [:octicons-home-16: Homepage](https://orgmode.org){ .md-button .md-button--primary }
    [:octicons-info-16:](https://orgmode.org/manuals.html){ .card-link title=Documentazione}
    [:octicons-code-16:](https://git.savannah.gnu.org/cgit/emacs/org-mode.git){ .card-link title="Codice sorgente" }
    [:octicons-heart-16:](https://liberapay.com/bzg){ .card-link title=Contributo }

## Criteri

**Si noti che non siamo affiliati a nessuno dei progetti che raccomandiamo.** Oltre ai [ nostri criteri standard](about/criteria.md), abbiamo sviluppato una serie di requisiti chiari che ci consentono di fornire raccomandazioni obiettive. Ti consigliamo di familiarizzare con questo elenco prima di scegliere di utilizzare un progetto e di condurre le vostre ricerche per assicurarvi che sia la scelta giusta per voi.

!!! esempio "Questa sezione è nuova"

    Stiamo lavorando per stabilire criteri ben definiti per ogni sezione del nostro sito, e questo potrebbe essere soggetto a modifiche. Se avete domande sui nostri criteri, vi preghiamo di [chiedere sul nostro forum](https://discuss.privacyguides.net/latest) e non date per scontato che non abbiamo preso in considerazione qualcosa nel formulare le nostre raccomandazioni se non è elencato qui. Sono molti i fattori presi in considerazione e discussi quando consigliamo un progetto, e stiamo lavorando per documentare ogni singolo fattore.

- I client devono essere open-source.
- Qualsiasi funzionalità di sincronizzazione nel cloud deve essere E2EE.
- Deve supportare l'esportazione di documenti in un formato standard.

### Il caso migliore

- La funzionalità di backup/sincronizzazione locale dovrebbe supportare la crittografia.
- Le piattaforme basate sul cloud dovrebbero supportare la condivisione dei documenti.