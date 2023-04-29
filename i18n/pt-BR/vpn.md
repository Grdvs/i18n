---
meta_title: "Recomendações e Comparação de Serviços VPN Privados, Sem Patrocinadores ou Anúncios — Privacy Guides"
title: "Serviços de VPN"
icon: material/vpn
description: Estes são os melhores serviços VPN para proteger sua privacidade e segurança on-line. Encontre aqui um provedor que não tem como objetivo espionar você.
cover: vpn.png
---

Se você está procurando mais **privacidade** do seu provedor de internet (ISP), ou em uma rede Wi-Fi pública, ou ao fazer torrent de arquivos, uma VPN pode ser a solução para você, desde que entenda os riscos envolvidos. Nós entendemos que estes provedores estão acima dos demais:

<div class="grid cards" markdown>

- ![IVPN logo](assets/img/vpn/mini/ivpn.svg){ .twemoji } [IVPN](#ivpn)
- ![Mullvad logo](assets/img/vpn/mullvad.svg){ .twemoji } [Mullvad](#mullvad)
- ![Proton VPN logo](assets/img/vpn/protonvpn.svg){ .twemoji } [Proton VPN](#proton-vpn)

</div>

!!! danger "As VPNs não proporcionam anonimato"

    Usar uma VPN **não** manterá seus hábitos de navegação anônimos, nem adicionará segurança ao tráfego não seguro (HTTP).
    
    Se você está procurando por **anonimato**, você deve usar o Navegador Tor **ao invés de ** de uma VPN.
    
    Se você está procurando por * * segurança * * adicional, você sempre deve verificar se está se conectando a sites que usam HTTPS. Uma VPN não substitui boas práticas de segurança.
    
    [Baixar Tor Browser](https://www.torproject.org/){ .md-button .md-button--primary } [Mitos sobre o Tor Browser & FAQ](advanced/tor-overview.md){ .md-button }

[Detalhes sobre VPNs :material-arrow-right-drop-circle:](basics/vpn-overview.md ""){.md-button}

## Provedores Recomendados

Nossos provedores recomendados usam criptografia, aceitam Monero, suportam WireGuard & OpenVPN, e têm uma política de não registro. Leia nossa [lista completa de requisitos](#criteria) para mais informações.

### IVPN

!!! recommendation

    ![IVPN logo](assets/img/vpn/ivpn.svg){ align=right }
    
    **IVPN** is another premium VPN provider, and they have been in operation since 2009. A IVPN está sediada em Gibraltar.
    
    [:octicons-home-16: Homepage](https://www.ivpn.net/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://www.ivpn.net/privacy/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://www.ivpn.net/knowledgebase/general/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/ivpn){ .card-link title="Source Code" }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=net.ivpn.client)
        - [:octicons-moon-16: Accrescent](https://accrescent.app/app/net.ivpn.client)
        - [:simple-appstore: App Store](https://apps.apple.com/app/ivpn-serious-privacy-protection/id1193122683)
        - [:simple-windows11: Windows](https://www.ivpn.net/apps-windows/)
        - [:simple-apple: macOS](https://www.ivpn.net/apps-macos/)
        - [:simple-linux: Linux](https://www.ivpn.net/apps-linux/)

#### :material-check:{ .pg-green } 35 Countries

IVPN tem [servidores em 35 países](https://www.ivpn.net/server-locations). (1) Escolher um provedor VPN com um servidor mais próximo de você reduzirá a latência do tráfego de rede que você envia. Isto deve-se a um caminho mais curto (menos pulos) até ao destino.
{ .annotate }

1. Última verificação: 16-09-2022

Nós também consideramos que é melhor para a segurança das chaves privadas do provedor VPN se eles usarem [servidores dedicados](https://en.wikipedia.org/wiki/Dedicated_hosting_service), em vez de soluções compartilhadas mais baratas (com outros clientes) como [servidores virtuais privados](https://pt.wikipedia.org/wiki/Servidor_virtual_privado).

#### :material-check:{ .pg-green } Examinado por auditores externos

IVPN foi submetido a uma [auditoria de ausência de registro de dados (no-logging) pela Cure53](https://cure53.de/audit-report_ivpn.pdf), cuja conclusão confirmou a reivindicação de que o IVPN não registra dados. IVPN também elaborou um [relatório completo de Teste de Penetração (pentest) pela Cure53](https://cure53.de/summary-report_ivpn_2019.pdf) em janeiro de 2020. IVPN também disse que eles planejam ter [relatórios anuais](https://www.ivpn.net/blog/independent-security-audit-concluded) no futuro. Uma revisão adicional foi feita [em abril de 2022](https://www.ivpn.net/blog/ivpn-apps-security-audit-2022-concluded/) e foi publicada pela Cure53 [em seu site](https://cure53.de/pentest-report_IVPN_2022.pdf).

#### :material-check:{ .pg-green } Clientes de Código Aberto (Open-Source)

A partir de fevereiro de 2020, [aplicativos IVPN agora são de código aberto](https://www.ivpn.net/blog/ivpn-applications-are-now-open-source). O código-fonte pode ser obtido da sua [organização (GitHub)](https://github.com/ivpn).

#### :material-check:{ .pg-green } Aceita Dinheiro e Monero

Além de aceitar cartões de crédito/débito e PayPal, IVPN aceita Bitcoin, **Monero** e **dinheiro/moeda local** (em planos anuais) como formas anônimas de pagamento.

#### :material-check:{ .pg-green } Suporta WireGuard

IVPN suporta o protocolo WireGuard®️. [WireGuard](https://www.wireguard.com) é um protocolo mais recente que usa criptografia de última geração [](https://www.wireguard.com/protocol/). Além disso, WireGuard pretende ser mais simples e mais eficiente.

IVPN [recomenda](https://www.ivpn.net/wireguard/) o uso do WireGuard em seu serviço e, sendo assim, ele é o protocolo padrão em todos os aplicativos do IVPN. O IVPN também oferece um gerador de configuração do WireGuard para ser usado com os [aplicativos](https://www.wireguard.com/install/) oficiais do WireGuard.

#### :material-check:{ .pg-green } Redirecionamento de Portas Remoto

O [redirecionamento de portas](https://pt.wikipedia.org/wiki/Redirecionamento_de_portas) remoto é possível com um plano Pro. Redirecionamento de portas [ pode ser ativado](https://www.ivpn.net/knowledgebase/81/How-do-I-activate-port-forwarding.html) através da área do cliente. O redirecionamento de portas só está disponível no IVPN ao usar os protocolos WireGuard ou OpenVPN e está [desativado nos servidores dos EUA](https://www.ivpn.net/knowledgebase/116/Port-forwarding-is-not-working-why.html).

#### :material-check:{ .pg-green } Clientes Móveis

Além de disponibilizar os arquivos de configuração padrão do OpenVPN, o IVPN tem aplicativos móveis disponíveis na [App Store](https://apps.apple.com/us/app/ivpn-serious-privacy-protection/id1193122683), [Google Play](https://play.google.com/store/apps/details?id=net.ivpn.client) e [GitHub](https://github.com/ivpn/android-app/releases), facilitando a conexão com seus servidores.

#### :material-information-outline:{ .pg-blue } Funcionalidades Adicionais

Aplicativos IVPN suportam autenticação de dois fatores (aplicativos Mullvad não suportam). IVPN também oferece a função "[AntiTracker](https://www.ivpn.net/antitracker)", que bloqueia redes de anúncios e rastreadores desde o nível da rede.

### Mullvad

!!! recommendation

    ![Mullvad logo](assets/img/vpn/mullvad.svg){ align=right }
    
    **Mullvad** é uma VPN rápida e barata com uma séria ênfase em transparência e segurança. Eles estão ativos desde **2009***. Mullvad está localizado na Suécia e não oferece um teste gratuito de avaliação.
    
    [:octicons-home-16: Homepage](https://mullvad.net){ .md-button .md-button--primary }
    [:simple-torbrowser:](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion){ .card-link title="Onion Service" }
    [:octicons-eye-16:](https://mullvad.net/en/help/privacy-policy/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://mullvad.net/en/help/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/mullvad){ .card-link title="Source Code" }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=net.mullvad.mullvadvpn)
        - [:simple-appstore: App Store](https://apps.apple.com/app/mullvad-vpn/id1488466513)
        - [:simple-github: GitHub](https://github.com/mullvad/mullvadvpn-app/releases)
        - [:simple-windows11: Windows](https://mullvad.net/en/download/windows/)
        - [:simple-apple: macOS](https://mullvad.net/en/download/macos/)
        - [:simple-linux: Linux](https://mullvad.net/en/download/linux/)

#### :material-check:{ .pg-green } 41 Países

Mullvad tem [servidores em 41 países](https://mullvad.net/servers/). (1) Escolher um provedor VPN com um servidor mais próximo de você reduzirá a latência do tráfego de rede que você envia. Isto deve-se a um caminho mais curto (menos pulos) até ao destino.
{ .annotate }

1. Última verificação: 16-09-2022

Nós também consideramos que é melhor para a segurança das chaves privadas do provedor VPN se eles usarem [servidores dedicados](https://en.wikipedia.org/wiki/Dedicated_hosting_service), em vez de soluções compartilhadas mais baratas (com outros clientes) como [servidores virtuais privados](https://pt.wikipedia.org/wiki/Servidor_virtual_privado).

#### :material-check:{ .pg-green } Examinado por auditores externos

Mullvad's VPN clients have been audited by Cure53 and Assured AB in a pentest report [published at cure53.de](https://cure53.de/pentest-report_mullvad_v2.pdf). The security researchers concluded:

> Cure53 and Assured AB are happy with the results of the audit and the software leaves an overall positive impression. With security dedication of the in-house team at the Mullvad VPN compound, the testers have no doubts about the project being on the right track from a security standpoint.

In 2020 a second audit [was announced](https://mullvad.net/blog/2020/6/25/results-available-audit-mullvad-app/) and the [final audit report](https://cure53.de/pentest-report_mullvad_2020_v2.pdf) was made available on Cure53's website:

> The results of this May-June 2020 project targeting the Mullvad complex are quite positive. [...] The overall application ecosystem used by Mullvad leaves a sound and structured impression. The overall structure of the application makes it easy to roll out patches and fixes in a structured manner. More than anything, the findings spotted by Cure53 showcase the importance of constantly auditing and re-assessing the current leak vectors, in order to always ensure privacy of the end-users. With that being said, Mullvad does a great job protecting the end-user from common PII leaks and privacy related risks.

In 2021 an infrastructure audit [was announced](https://mullvad.net/en/blog/2021/1/20/no-pii-or-privacy-leaks-found-cure53s-infrastructure-audit/) and the [final audit report](https://cure53.de/pentest-report_mullvad_2021_v1.pdf) was made available on Cure53's website. Another report was commissioned [in June 2022](https://mullvad.net/en/blog/2022/6/22/vpn-server-audit-found-no-information-leakage-or-logging-of-customer-data/) and is available on [Assured's website](https://www.assured.se/publications/Assured_Mullvad_relay_server_audit_report_2022.pdf).

#### :material-check:{ .pg-green } Clientes de Código Aberto (Open-Source)

Mullvad provides the source code for their desktop and mobile clients in their [GitHub organization](https://github.com/mullvad/mullvadvpn-app).

#### :material-check:{ .pg-green } Aceita Dinheiro e Monero

Mullvad, além de aceitar cartões de crédito/débito e PayPal, aceita Bitcoin, Bitcoin Cash, **Monero** e **dinheiro / moeda local** como formas anônimas de pagamento. Eles também aceitam Swish e transferências bancárias.

#### :material-check:{ .pg-green } Suporta WireGuard

Mullvad suporta o protocolo WireGuard®. [WireGuard](https://www.wireguard.com) é um protocolo mais recente que usa criptografia de última geração [](https://www.wireguard.com/protocol/). Além disso, WireGuard pretende ser mais simples e mais eficiente.

Mullvad [recomenda](https://mullvad.net/en/help/why-wireguard/) o uso do WireGuard em seu serviço. It is the default or only protocol on Mullvad's Android, iOS, macOS, and Linux apps, but on Windows you have to [manually enable](https://mullvad.net/en/help/how-turn-wireguard-mullvad-app/) WireGuard. Mullvad also offers a WireGuard configuration generator for use with the official WireGuard [apps](https://www.wireguard.com/install/).

#### :material-check:{ .pg-green } IPv6 Support

Mullvad supports the future of networking [IPv6](https://en.wikipedia.org/wiki/IPv6). Their network allows you to [access services hosted on IPv6](https://mullvad.net/en/blog/2014/9/15/ipv6-support/) as opposed to other providers who block IPv6 connections.

#### :material-check:{ .pg-green } Redirecionamento de Portas Remoto

Remote [port forwarding](https://en.wikipedia.org/wiki/Port_forwarding) is allowed for people who make one-time payments, but not allowed for accounts with a recurring/subscription-based payment method. This is to prevent Mullvad from being able to identify you based on your port usage and stored subscription information. See [Port forwarding with Mullvad VPN](https://mullvad.net/help/port-forwarding-and-mullvad/) for more information.

#### :material-check:{ .pg-green } Clientes Móveis

Mullvad has published [App Store](https://apps.apple.com/app/mullvad-vpn/id1488466513) and [Google Play](https://play.google.com/store/apps/details?id=net.mullvad.mullvadvpn) clients, both supporting an easy-to-use interface as opposed to requiring you to manually configure your WireGuard connection. The Android client is also available on [GitHub](https://github.com/mullvad/mullvadvpn-app/releases).

#### :material-information-outline:{ .pg-blue } Funcionalidades Adicionais

Mullvad is very transparent about which nodes they [own or rent](https://mullvad.net/en/servers/). They use [ShadowSocks](https://shadowsocks.org/) in their ShadowSocks + OpenVPN configuration, making them more resistant against firewalls with [Deep Packet Inspection](https://en.wikipedia.org/wiki/Deep_packet_inspection) trying to block VPNs. Supposedly, [China has to use a different method to block ShadowSocks servers](https://github.com/net4people/bbs/issues/22). Mullvad's website is also accessible via Tor at [o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion).

### Proton VPN

!!! anotar recomendação

    ![Logomarca ProtonVPN](assets/img/vpn/protonvpn.svg){ align=right }
    
    **Proton VPN** é um forte concorrente no espaço VPN, e estão em funcionamento desde 2016. Proton AG está sediada na Suíça e oferece um plano gratuito limitado, bem como uma opção paga com mais recursos.
    
    [:octicons-home-16: Página Inicial](https://protonvpn.com/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://protonvpn.com/privacy-policy){ .card-link title="Política de Privacidade" }
    [:octicons-info-16:](https://protonvpn.com/support/){ .card-link title=Documentação}
    [:octicons-code-16:](https://github.com/ProtonVPN){ .card-link title="Código Fonte" }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=ch.protonvpn.android)
        - [:simple-appstore: App Store](https://apps.apple.com/app/apple-store/id1437005085)
        - [:simple-github: GitHub](https://github.com/ProtonVPN/android-app/releases)
        - [:simple-windows11: Windows](https://protonvpn.com/download-windows)
        - [:simple-linux: Linux](https://protonvpn.com/support/linux-vpn-setup/)

#### :material-check:{ .pg-green } 67 Countries

Proton VPN has [servers in 67 countries](https://protonvpn.com/vpn-servers).(1) Picking a VPN provider with a server nearest to you will reduce latency of the network traffic you send. Isto deve-se a um caminho mais curto (menos pulos) até ao destino.
{ .annotate }

1. Última verificação: 16-09-2022

Nós também consideramos que é melhor para a segurança das chaves privadas do provedor VPN se eles usarem [servidores dedicados](https://en.wikipedia.org/wiki/Dedicated_hosting_service), em vez de soluções compartilhadas mais baratas (com outros clientes) como [servidores virtuais privados](https://pt.wikipedia.org/wiki/Servidor_virtual_privado).

#### :material-check:{ .pg-green } Examinado por auditores externos

Em Janeiro de 2020, ProtonVPN foi submetida a uma auditoria independente pela SEC Consult. A SEC Consult encontrou algumas vulnerabilidades de médio e baixo risco nos aplicativos Windows, Android e iOS da Proton VPN, todos os quais foram "devidamente corrigidos" pela Proton VPN antes que os relatórios fossem publicados. Nenhum dos problemas identificados teria proporcionado acesso remoto ao seu dispositivo ou tráfego. Você pode ver os relatórios individuais para cada plataforma em [protonvpn.com](https://protonvpn.com/blog/open-source/). Em abril de 2022 Proton VPN passou por [outra auditoria](https://protonvpn.com/blog/no-logs-audit/) e o relatório foi [produzido pelo Securitum](https://protonvpn.com/blog/wp-content/uploads/2022/04/securitum-protonvpn-nologs-20220330.pdf). Um [certificado de segurança](https://proton.me/blog/security-audit-all-proton-apps) foi concedido para os aplicativos do Proton Mail em 9 de Novembro de 2021 pela [Securitium](https://research.securitum.com).

#### :material-check:{ .pg-green } Clientes de Código Aberto (Open-Source)

Proton VPN provides the source code for their desktop and mobile clients in their [GitHub organization](https://github.com/ProtonVPN).

#### :material-check:{ .pg-green } Accepts Cash

Proton VPN, in addition to accepting credit/debit cards, PayPal, and [Bitcoin](advanced/payments.md#other-coins-bitcoin-ethereum-etc), also accepts **cash/local currency** as an anonymous form of payment.

#### :material-check:{ .pg-green } Suporta WireGuard

Proton VPN suporta principalmente o protocolo WireGuard®. [WireGuard](https://www.wireguard.com) é um protocolo mais recente que usa criptografia de última geração [](https://www.wireguard.com/protocol/). Além disso, WireGuard pretende ser mais simples e mais eficiente.

Proton VPN [recommends](https://protonvpn.com/blog/wireguard/) the use of WireGuard with their service. On Proton VPN's Windows, macOS, iOS, Android, ChromeOS, and Android TV apps, WireGuard is the default protocol; however, [support](https://protonvpn.com/support/how-to-change-vpn-protocols/) for the protocol is not present in their Linux app.

#### :material-alert-outline:{ .pg-orange } Remote Port Forwarding

Proton VPN currently only supports remote [port forwarding](https://protonvpn.com/support/port-forwarding/) on Windows, which may impact some applications. Especially Peer-to-peer applications like Torrent clients.

#### :material-check:{ .pg-green } Clientes Móveis

In addition to providing standard OpenVPN configuration files, Proton VPN has mobile clients for [App Store](https://apps.apple.com/us/app/protonvpn-fast-secure-vpn/id1437005085), [Google Play](https://play.google.com/store/apps/details?id=ch.protonvpn.android&hl=en_US), and [GitHub](https://github.com/ProtonVPN/android-app/releases) allowing for easy connections to their servers.

#### :material-information-outline:{ .pg-blue } Funcionalidades Adicionais

Proton VPN clients support two factor authentication on all platforms except Linux at the moment. Proton VPN has their own servers and datacenters in Switzerland, Iceland and Sweden. They offer adblocking and known malware domains blocking with their DNS service. Additionally, Proton VPN also offers "Tor" servers allowing you to easily connect to onion sites, but we still strongly recommend using [the official Tor Browser](https://www.torproject.org/) for this purpose.

#### :material-alert-outline:{ .pg-orange } Killswitch feature is broken on Intel-based Macs

System crashes [may occur](https://protonvpn.com/support/macos-t2-chip-kill-switch/) on Intel-based Macs when using the VPN killswitch. If you require this feature, and you are using a Mac with Intel chipset, you should consider using another VPN service.

## Criteria

!!! aviso
    Você **nunca** deve instalar quaisquer extensões adicionais no Tor Browser, incluindo as que sugerimos para o Firefox.

    It is important to note that using a VPN provider will not make you anonymous, but it will give you better privacy in certain situations. A VPN is not a tool for illegal activities. Não confie somente numa política de "não-rastreamento".

**Please note we are not affiliated with any of the providers we recommend. This allows us to provide completely objective recommendations.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements for any VPN provider wishing to be recommended, including strong encryption, independent security audits, modern technology, and more. We suggest you familiarize yourself with this list before choosing a VPN provider, and conduct your own research to ensure the VPN provider you choose is as trustworthy as possible.

### Technology

We require all our recommended VPN providers to provide OpenVPN configuration files to be used in any client. **If** a VPN provides their own custom client, we require a killswitch to block network data leaks when disconnected.

**Minimum to Qualify:**

- Support for strong protocols such as WireGuard & OpenVPN.
- Killswitch built in to clients.
- Multihop support. Multihopping is important to keep data private in case of a single node compromise.
- If VPN clients are provided, they should be [open-source](https://en.wikipedia.org/wiki/Open_source), like the VPN software they generally have built into them. We believe that [source code](https://en.wikipedia.org/wiki/Source_code) availability provides greater transparency about what your device is actually doing.

**Best Case:**

- WireGuard and OpenVPN support.
- Killswitch with highly configurable options (enable/disable on certain networks, on boot, etc.)
- Easy-to-use VPN clients
- Supports [IPv6](https://en.wikipedia.org/wiki/IPv6). We expect that servers will allow incoming connections via IPv6 and allow you to access services hosted on IPv6 addresses.
- Capability of [remote port forwarding](https://en.wikipedia.org/wiki/Port_forwarding#Remote_port_forwarding) assists in creating connections when using P2P ([Peer-to-Peer](https://en.wikipedia.org/wiki/Peer-to-peer)) file sharing software or hosting a server (e.g., Mumble).

### Privacy

We prefer our recommended providers to collect as little data as possible. Not collecting personal information on registration, and accepting anonymous forms of payment are required.

**Minimum to Qualify:**

- [Criptomoeda anônima](cryptocurrency.md) **ou** opção de pagamento em dinheiro.
- No personal information required to register: Only username, password, and email at most.

**Best Case:**

- Aceita múltiplas [opções de pagamento anônimas](advanced/payments.md).
- Nenhuma informação pessoal é aceita (nome de usuário gerado automaticamente, nenhum e-mail necessário, etc.).

### Security

A VPN is pointless if it can't even provide adequate security. We require all our recommended providers to abide by current security standards for their OpenVPN connections. Ideally, they would use more future-proof encryption schemes by default. We also require an independent third-party to audit the provider's security, ideally in a very comprehensive manner and on a repeated (yearly) basis.

**Minimum to Qualify:**

- Strong Encryption Schemes: OpenVPN with SHA-256 authentication; RSA-2048 or better handshake; AES-256-GCM or AES-256-CBC data encryption.
- Perfect Forward Secrecy (PFS).
- Published security audits from a reputable third-party firm.

**Best Case:**

- Strongest Encryption: RSA-4096.
- Perfect Forward Secrecy (PFS).
- Comprehensive published security audits from a reputable third-party firm.
- Bug-bounty programs and/or a coordinated vulnerability-disclosure process.

### Trust

You wouldn't trust your finances to someone with a fake identity, so why trust them with your internet data? We require our recommended providers to be public about their ownership or leadership. We also would like to see frequent transparency reports, especially in regard to how government requests are handled.

**Minimum to Qualify:**

- Public-facing leadership or ownership.

**Best Case:**

- Public-facing leadership.
- Frequent transparency reports.

### Marketing

With the VPN providers we recommend we like to see responsible marketing.

**Minimum to Qualify:**

- Must self-host analytics (i.e., no Google Analytics). The provider's site must also comply with [DNT (Do Not Track)](https://en.wikipedia.org/wiki/Do_Not_Track) for people who want to opt-out.

Must not have any marketing which is irresponsible:

- Making guarantees of protecting anonymity 100%. When someone makes a claim that something is 100% it means there is no certainty for failure. We know people can quite easily deanonymize themselves in a number of ways, e.g.:
    - Reusing personal information (e.g., email accounts, unique pseudonyms, etc.) that they accessed without anonymity software (Tor, VPN, etc.)
    - [Browser fingerprinting](https://en.wikipedia.org/wiki/Device_fingerprint#Browser_fingerprint)
- Claim that a single circuit VPN is "more anonymous" than Tor, which is a circuit of three or more hops that regularly changes.
- Use responsible language: i.e., it is okay to say that a VPN is "disconnected" or "not connected", however claiming that someone is "exposed", "vulnerable" or "compromised" is needless use of alarming language that may be incorrect. For example, that person might simply be on another VPN provider's service or using Tor.

**Best Case:**

Responsible marketing that is both educational and useful to the consumer could include:

- An accurate comparison to when [Tor](tor.md) should be used instead.
- Availability of the VPN provider's website over a [.onion service](https://en.wikipedia.org/wiki/.onion)

### Additional Functionality

While not strictly requirements, there are some factors we looked into when determining which providers to recommend. These include adblocking/tracker-blocking functionality, warrant canaries, multihop connections, excellent customer support, the number of allowed simultaneous connections, etc.