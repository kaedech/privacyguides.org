---
title: "Email Clients"
icon: material/email-open
---

Our recommendation list contains email clients that support both [OpenPGP](encryption.md#openpgp) and strong authentication such as [Open Authorization (OAuth)](https://en.wikipedia.org/wiki/OAuth). OAuth allows you to use [Multi-Factor Authentication](basics/multi-factor-authentication.md) and prevent account theft.

??? warning "Email does not provide forward secrecy"

    When using end-to-end encryption (E2EE) technology like OpenPGP, email will still have [some metadata](email.md#email-metadata-overview) that is not encrypted in the header of the email.
    
    OpenPGP also does not support [forward secrecy](https://en.wikipedia.org/wiki/Forward_secrecy), which means if either your or the recipient's private key is ever stolen, all previous messages encrypted with it will be exposed: [How do I protect my private keys?](basics/email-security.md) Consider using a medium that provides forward secrecy:
    
    [Real-time Communication](real-time-communication.md){ .md-button }

## Cross-Platform

### Thunderbird

!!! khuyến nghị

    ![Thunderbird logo](assets/img/email-clients/thunderbird.svg){ align=right }
    
    **Thunderbird** is a free, open-source, cross-platform email, newsgroup, news feed, and chat (XMPP, IRC, Twitter) client developed by the Thunderbird community, and previously by the Mozilla Foundation.
    
    [Homepage](https://www.thunderbird.net){ .md-button .md-button--primary } [Chính Sách Bảo Mật](https://www.mozilla.org/privacy/thunderbird){ .md-button }
    
    ??? tải xuống
    
        - [:fontawesome-brands-windows: Windows](https://www.thunderbird.net)
        - [:fontawesome-brands-apple: macOS](https://www.thunderbird.net)
        - [:fontawesome-brands-linux: Linux](https://www.thunderbird.net)
        - [:pg-flathub: Flatpak](https://flathub.org/apps/details/org.mozilla.Thunderbird)
        - [:fontawesome-brands-git: Mã nguồn](https://hg.mozilla.org/comm-central)

#### Recommended Configuration

We recommend changing some of these settings to make Thunderbird a little more private.

These options can be found in :material-menu: → **Settings** → **Privacy & Security**.

##### Web Content

- [ ] Uncheck  **Remember websites and links I've visited**
- [ ] Uncheck  **Accept cookies from sites**

##### Telemetry

- [ ] Uncheck  **Allow Thunderbird to send technical and interaction data to Mozilla**

#### Thunderbird-user.js (advanced)

[`thunderbird-user.js`](https://github.com/HorlogeSkynet/thunderbird-user.js), is a set of configurations options that aims to disable as many of the web-browsing features within Thunderbird as possible in order to reduce surface area and maintain privacy. Some of the changes are backported from the [Arkenfox project](https://github.com/arkenfox/user.js).

## Platform Specific

### Apple Mail (macOS)

!!! khuyến nghị

    ![Apple Mail logo](assets/img/email-clients/applemail.png){ align=right }
    
    **Apple Mail** is included in macOS and can be extended to have OpenPGP support with [GPG Suite](encryption.md#gpg-suite), which adds the ability to send PGP-encrypted email.
    
    [:octicons-home-16: Homepage](https://support.apple.com/guide/mail/welcome/mac){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://www.apple.com/legal/privacy/en-ww/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://support.apple.com/guide/mail/toc){ .card-link title=Documentation}

### Canary Mail (iOS)

!!! khuyến nghị

    ![Canary Mail logo](assets/img/email-clients/canarymail.svg){ align=right }
    
    **Canary Mail** is a paid email client designed to make end-to-end encryption seamless with security features such as a biometric app lock.
    
    [Website](https://support.apple.com/guide/mail/welcome/mac){ .md-button .md-button--primary } [Chính Sách Bảo Mật](https://www.apple.com/legal/privacy/en-ww/){ .md-button } downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=io.canarymail.android)
        - [:simple-appstore: App Store](https://apps.apple.com/app/id1236045954)
        - [:simple-windows11: Windows](https://canarymail.io/downloads.html)

!!! warning

    Canary Mail only recently released a Windows and Android client, though we don't believe they are as stable as their iOS and Mac counterparts.

Canary Mail is closed-source. We recommend it due to the few choices there are for email clients on iOS that support PGP E2EE.

### FairEmail (Android)

!!! khuyến nghị

    ![FairEmail logo](assets/img/email-clients/fairemail.svg){ align=right }
    
    **FairEmail** is a minimal, open-source email app, using open standards (IMAP, SMTP, OpenPGP) with a low data and battery usage.
    
    [:octicons-home-16: Homepage](https://email.faircode.eu){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://github.com/M66B/FairEmail/blob/master/PRIVACY.md){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://github.com/M66B/FairEmail/blob/master/FAQ.md){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/M66B/FairEmail){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://email.faircode.eu/donate/){ .card-link title=Contribute }
    
    ??? [Website](https://kontact.kde.org){ .md-button .md-button--primary } [Chính Sách Bảo Mật](https://kde.org/privacypolicy-apps){ .md-button }
    
    ???

### GNOME Evolution (GNOME)

!!! khuyến nghị

    ![Evolution logo](assets/img/email-clients/evolution.svg){ align=right }
    
    **Evolution** is a personal information management application that provides integrated mail, calendaring and address book functionality. [Homepage](https://www.mailvelope.com){ .md-button .md-button--primary } [Chính Sách Bảo Mật](https://www.mailvelope.com/en/privacy-policy){ .md-button }
    
    ???
    
    tải xuống
    
        - [:fontawesome-brands-firefox: Firefox](https://addons.mozilla.org/firefox/addon/mailvelope)
        - [:fontawesome-brands-chrome: Chrome](https://chrome.google.com/webstore/detail/mailvelope/kajibbejlbohfaggdiogboambcijhkke)
        - [:fontawesome-brands-edge: Edge](https://microsoftedge.microsoft.com/addons/detail/mailvelope/dgcbddhdhjppfdfjpciagmmibadmoapc)
        - [:fontawesome-brands-github: Mã nguồn](https://github.com/mailvelope/mailvelope) downloads
    
        - [:simple-flathub: Flathub](https://flathub.org/apps/details/org.gnome.Evolution)

### K-9 Mail (Android)

!!! khuyến nghị

    ![K-9 Mail logo](assets/img/email-clients/k9mail.svg){ align=right }
    
    **K-9 Mail** is an independent mail application that supports both POP3 and IMAP mailboxes, but only supports push mail for IMAP.
    
    [Homepage](https://k9mail.app){ .md-button .md-button--primary } [Chính Sách Bảo Mật](https://k9mail.app/privacy){ .md-button }
    
    ???
    
    tải xuống
    
        - [:fontawesome-brands-google-play: Google Play](https://play.google.com/store/apps/details?id=com.fsck.k9)
        - [:pg-f-droid: F-Droid](https://f-droid.org/packages/com.fsck.k9)
        - [:fontawesome-brands-github: Mã nguồn](https://github.com/k9mail) downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=com.fsck.k9)
        - [:simple-github: GitHub](https://github.com/k9mail/k-9/releases)

!!! warning

    When replying to someone on a mailing list the "reply" option may also include the mailing list. [Homepage](https://email.faircode.eu){ .md-button .md-button--primary } [Chính Sách Bảo Mật](https://github.com/M66B/FairEmail/blob/master/PRIVACY.md){ .md-button }
    
    ???

### Kontact (KDE)

!!! khuyến nghị

    ![Kontact logo](assets/img/email-clients/kontact.svg){ align=right }
    
    **Kontact** is a personal information manager (PIM) application from the [KDE](https://kde.org) project. It provides a mail client, address book, organizer and RSS client.
    
    [:octicons-home-16: Homepage](https://kontact.kde.org){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://kde.org/privacypolicy-apps){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://kontact.kde.org/users/){ .card-link title=Documentation}
    [:octicons-code-16:](https://invent.kde.org/pim/kmail){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://kde.org/community/donations/){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-linux: Linux](https://kontact.kde.org/download)
        - [:simple-flathub: Flathub](https://flathub.org/apps/details/org.kde.kontact)

### Mailvelope (Browser)

!!! khuyến nghị

    ![Mailvelope logo](assets/img/email-clients/mailvelope.svg){ align=right }
    
    **Mailvelope** is a browser extension that enables the exchange of encrypted emails following the OpenPGP encryption standard.
    
    [:octicons-home-16: Homepage](https://www.mailvelope.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://www.mailvelope.com/en/privacy-policy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://mailvelope.com/faq){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/mailvelope/mailvelope){ .card-link title="Source Code" }
    
    ??? downloads
    
        - [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/firefox/addon/mailvelope)
        - [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/mailvelope/kajibbejlbohfaggdiogboambcijhkke)
        - [:simple-microsoftedge: Edge](https://microsoftedge.microsoft.com/addons/detail/mailvelope/dgcbddhdhjppfdfjpciagmmibadmoapc)

### NeoMutt (CLI)

!!! khuyến nghị

    ![NeoMutt logo](assets/img/email-clients/mutt.svg){ align=right }
    
    **NeoMutt** is an open-source command line mail reader (or MUA) for Linux and BSD. It's a fork of [Mutt](https://en.wikipedia.org/wiki/Mutt_(email_client)) with added features.
    
    NeoMutt is a text-based client that has a steep learning curve. It is however, very customizable.
    
    [:octicons-home-16: Homepage](https://neomutt.org){ .md-button .md-button--primary }
    [:octicons-info-16:](https://neomutt.org/guide/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/neomutt/neomutt){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://www.paypal.com/paypalme/russon/){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-apple: macOS](https://neomutt.org/distro)
        - [:simple-linux: Linux](https://neomutt.org/distro)

## Framadate

**Please note we are not affiliated with any of the projects we recommend.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements to allow us to provide objective recommendations. We suggest you familiarize yourself with this list before choosing to use a project, and conduct your own research to ensure it's the right choice for you.

!!! cảnh báo
    PrivateBin sử dụng JavaScript để xử lý mã hóa, vì vậy bạn phải tin tưởng nhà cung cấp ở mức độ họ không đưa bất kỳ JavaScript độc hại nào vào để lấy khóa cá nhân của bạn.

    ![PrivateBin logo](assets/img/productivity/privatebin.svg){ align=right }
    
    **PrivateBin** là một pastebin trực tuyến mã nguồn mở, tối giản, nơi máy chủ không có kiến ​​thức về dữ liệu đã dán. Dữ liệu được mã hóa/giải mã trong trình duyệt bằng 256-bit AES. tải xuống
    
        - [:fontawesome-brands-docker: Dockerhub](https://hub.docker.com/r/vaultwarden/server)
        - [:fontawesome-brands-github: Mã nguồn](https://github.com/dani-garcia/vaultwarden)

### Minimum Qualifications

- Apps developed for open-source operating systems must be open-source.
- Must not collect telemetry, or have an easy way to disable all telemetry.
- Must support OpenPGP message encryption.

### Best-Case

Our best-case criteria represents what we would like to see from the perfect project in this category. Our recommendations may not include any or all of this functionality, but those which do may rank higher than others on this page.

- Should be open-source.
- Should be cross-platform.
- Should not collect any telemetry by default.
- Should support OpenPGP natively, i.e. without extensions.
- Should support storing OpenPGP encrypted emails locally.

--8<-- "includes/abbreviations.vi.txt"