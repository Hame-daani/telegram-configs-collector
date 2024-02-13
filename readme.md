## Introduction
The script aggregates Vmess, Vless, Reality, Trojan, and ShadowSocks configurations from Telegram public channels. It cleans up the configurations based on the open and closed ports, removes duplicate configurations, resolves configurations addresses based on IP address, and redefines configuration titles based on server and protocol type properties such as network and security type, IP address and port, and respective country.

![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/soroushmirzaei/telegram-configs-collector?label=Last%20Commit&color=%2338914b)
![GitHub](https://img.shields.io/github/license/soroushmirzaei/telegram-configs-collector?label=License&color=yellow)
![GitHub Repo stars](https://img.shields.io/github/stars/soroushmirzaei/telegram-configs-collector?label=Stars&color=red&style=flat)
![GitHub forks](https://img.shields.io/github/forks/soroushmirzaei/telegram-configs-collector?label=Forks&color=blue&style=flat)
[![Execute On Schedule](https://github.com/soroushmirzaei/telegram-configs-collector/actions/workflows/schedule.yml/badge.svg)](https://github.com/soroushmirzaei/telegram-configs-collector/actions/workflows/schedule.yml)
[![Execute On Push](https://github.com/soroushmirzaei/telegram-configs-collector/actions/workflows/push.yml/badge.svg)](https://github.com/soroushmirzaei/telegram-configs-collector/actions/workflows/push.yml)

## Tutorial
The list of domains to bypass, block and proxy based on `ir` geo-location in the `nekoray` and `nekobox` according to the core is set to `sing-box` . to set these domains just create new routes in the `nekobox` and `nekoray` and enter the domains below in the pertained section `domains` and set it's outbound value based on `bypass`, `proxy` or `block` as below.

- Bypass
```
geosite:category-bank-ir
geosite:category-bourse-ir
geosite:category-education-ir
geosite:category-forums-ir
geosite:category-gov-ir
geosite:category-insurance-ir
geosite:category-media-ir
geosite:category-news-ir
geosite:category-payment-ir
geosite:category-scholar-ir
geosite:category-shopping-ir
geosite:category-social-media-ir
geosite:category-tech-ir
geosite:category-travel-ir
```

- Proxy
```
geosite:apple
geosite:adobe
geosite:anthropic
geosite:openai
geosite:clubhouse
geosite:netflix
geosite:nvidia
geosite:intel
geosite:amd
geosite:signal
geosite:soundcloud
geosite:youtube
geosite:telegram
geosite:twitter
geosite:instagram
geosite:facebook
geosite:whatsapp
geosite:pinterest
geosite:tiktok
geosite:spotify
geosite:twitch
geosite:discord
```

- Block
```
geosite:category-ads-all
geosite:category-ads-ir
geosite:google-ads
geosite:spotify-ads
geosite:adobe-ads
geosite:apple-ads
```

## Protocol Type Subscription Links
Configuration subscription links based on protocol type and splitted based on Telegram channels and subscription links
| **Protocol Type** | **Mixed Configurations** | **Telegram Channels** | **Subscription Links** |
|:---:|:---:|:---:|:---:|
| **Juicity Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/juicity) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/juicity) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/juicity) |
| **Hysteria Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/hysteria) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/hysteria) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/hysteria) |
| **Tuic Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/tuic) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/tuic) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/tuic) |
| **Reality Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/reality) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/reality) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/reality) |
| **Vless Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/vless) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/vless) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/vless) |
| **Vmess Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/vmess) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/vmess) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/vmess) |
| **Trojan Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/trojan) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/trojan) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/trojan) |
| **Shadowsocks Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/protocols/shadowsocks) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/protocols/shadowsocks) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/protocols/shadowsocks) |
| **Mixed Type Configurations** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/splitted/mixed) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/splitted/channels) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/splitted/subscribe) |

## Network Type Subscription Links
Configuration subscription links based on network type and splitted based on Telegram channels and subscription links
| **Network Type** | **Mixed Configurations** | **Telegram Channels** | **Subscription Links** |
|:---:|:---:|:---:|:---:|
| **Google Remote Procedure Call (GRPC)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/networks/grpc) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/networks/grpc) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/networks/grpc) |
| **Hypertext Transfer Protocol (HTTP)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/networks/http) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/networks/http) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/networks/http) |
| **WebSocket Protocol (WS)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/networks/ws) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/networks/ws) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/networks/ws) |
 | **Transmission Control Protocol (TCP)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/networks/tcp) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/networks/tcp) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/networks/tcp) |

## Security Type Subscription Links
Configuration subscription links based on security type and splitted based on Telegram channels and subscription links
| **Security Type** | **Mixed Configurations** | **Telegram Channels** | **Subscription Links** |
|:---:|:---:|:---:|:---:|
| **Transport Layer Security (TLS)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/security/tls) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/security/tls) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/security/tls) |
| **Non Transport Layer Security (Non-TLS)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/security/non-tls) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/security/non-tls) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/security/non-tls) |

## Internet Protocol Type Subscription Links
Configuration subscription links based on internet protocol type and splitted based on Telegram channels and subscription links
| **Internet Protocol Type** | **Mixed Configurations** | **Telegram Channels** | **Subscription Links** |
|:---:|:---:|:---:|:---:|
| **Internet Protocol Version 4 (IPV4)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/layers/ipv4) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/layers/ipv4) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/layers/ipv4) |
| **Internet Protocol Version 6 (IPV6)** | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/layers/ipv6) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/channels/layers/ipv6) | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/subscribe/layers/ipv6) |

## Country Subscription Links
Configuration subscription links based on country for the services that the accounts would be banned  if the location is changed, such as social media and artificial intelligence services
| **Code** | **Country Name** | **Subscription Link** | **Code** | **Country Name** | **Subscription Link** |
|:---:|:---:|:---:|:---:|:---:|:---:|
| AL | Albania | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/al/mixed) | AR | Argentina | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ar/mixed) |
| AM | Armenia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/am/mixed) | AU | Australia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/au/mixed) |
| AT | Austria | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/at/mixed) | AZ | Azerbaijan | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/az/mixed) |
| BH | Bahrain | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/bh/mixed) | BD | Bangladesh | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/bd/mixed) |
| BY | Belarus | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/by/mixed) | BE | Belgium | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/be/mixed) |
| BZ | Belize | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/bz/mixed) | BT | Bhutan | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/bt/mixed) |
| BA | Bosnia and Herzegovina | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ba/mixed) | BR | Brazil | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/br/mixed) |
| BG | Bulgaria | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/bg/mixed) | CA | Canada | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ca/mixed) |
| CL | Chile | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/cl/mixed) | CN | China | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/cn/mixed) |
| CO | Colombia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/co/mixed) | CR | Costa Rica | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/cr/mixed) |
| HR | Croatia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/hr/mixed) | CW | Curaçao | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/cw/mixed) |
| CY | Cyprus | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/cy/mixed) | CZ | Czechia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/cz/mixed) |
| DK | Denmark | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/dk/mixed) | EC | Ecuador | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ec/mixed) |
| EG | Egypt | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/eg/mixed) | EE | Estonia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ee/mixed) |
| FI | Finland | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/fi/mixed) | FR | France | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/fr/mixed) |
| GE | Georgia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ge/mixed) | DE | Germany | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/de/mixed) |
| GR | Greece | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/gr/mixed) | GT | Guatemala | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/gt/mixed) |
| HK | Hong Kong | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/hk/mixed) | HU | Hungary | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/hu/mixed) |
| IS | Iceland | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/is/mixed) | IN | India | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/in/mixed) |
| ID | Indonesia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/id/mixed) | IR | Iran, Islamic Republic of | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ir/mixed) |
| IQ | Iraq | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/iq/mixed) | IE | Ireland | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ie/mixed) |
| IM | Isle of Man | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/im/mixed) | IL | Israel | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/il/mixed) |
| IT | Italy | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/it/mixed) | JP | Japan | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/jp/mixed) |
| KZ | Kazakhstan | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/kz/mixed) | KE | Kenya | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ke/mixed) |
| KR | Korea, Republic of | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/kr/mixed) | KG | Kyrgyzstan | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/kg/mixed) |
| LV | Latvia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/lv/mixed) | LY | Libya | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ly/mixed) |
| LT | Lithuania | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/lt/mixed) | LU | Luxembourg | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/lu/mixed) |
| MO | Macao | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/mo/mixed) | MY | Malaysia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/my/mixed) |
| MT | Malta | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/mt/mixed) | MU | Mauritius | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/mu/mixed) |
| MX | Mexico | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/mx/mixed) | MD | Moldova, Republic of | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/md/mixed) |
| MN | Mongolia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/mn/mixed) | MA | Morocco | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ma/mixed) |
| MM | Myanmar | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/mm/mixed) | NL | Netherlands | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/nl/mixed) |
| NG | Nigeria | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ng/mixed) | MK | North Macedonia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/mk/mixed) |
| NO | Norway | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/no/mixed) | NA | Not Available | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/na/mixed) |
| OM | Oman | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/om/mixed) | PK | Pakistan | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/pk/mixed) |
| PS | Palestine, State of | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ps/mixed) | PA | Panama | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/pa/mixed) |
| PE | Peru | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/pe/mixed) | PH | Philippines | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ph/mixed) |
| PL | Poland | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/pl/mixed) | PT | Portugal | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/pt/mixed) |
| PR | Puerto Rico | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/pr/mixed) | QA | Qatar | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/qa/mixed) |
| RO | Romania | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ro/mixed) | RU | Russian Federation | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ru/mixed) |
| RW | Rwanda | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/rw/mixed) | SA | Saudi Arabia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/sa/mixed) |
| RS | Serbia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/rs/mixed) | SC | Seychelles | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/sc/mixed) |
| SG | Singapore | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/sg/mixed) | SK | Slovakia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/sk/mixed) |
| SI | Slovenia | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/si/mixed) | ZA | South Africa | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/za/mixed) |
| ES | Spain | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/es/mixed) | SE | Sweden | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/se/mixed) |
| CH | Switzerland | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ch/mixed) | TW | Taiwan, Province of China | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/tw/mixed) |
| TJ | Tajikistan | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/tj/mixed) | TH | Thailand | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/th/mixed) |
| TR | Türkiye | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/tr/mixed) | UA | Ukraine | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ua/mixed) |
| AE | United Arab Emirates | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/ae/mixed) | GB | United Kingdom | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/gb/mixed) |
| US | United States | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/us/mixed) | UY | Uruguay | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/uy/mixed) |
| VN | Viet Nam | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/vn/mixed) | VG | Virgin Islands, British | [Subscription Link](https://raw.githubusercontent.com/soroushmirzaei/telegram-configs-collector/main/countries/vg/mixed) |
## Stats
[![Stars](https://starchart.cc/soroushmirzaei/telegram-configs-collector.svg?variant=adaptive)](https://starchart.cc/soroushmirzaei/telegram-configs-collector)