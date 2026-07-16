<div align="center">

<img src="https://cdn.simpleicons.org/meta/0866FF" width="90" alt="Meta logo" />

# Awesome Meta Platform [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated list of open-source tools, SDKs, and MCP servers for the Meta platform ecosystem — Marketing API (Ads), Graph API, Conversions API, WhatsApp Cloud API, Instagram, and Messenger.**

<img src="https://readme-typing-svg.demolab.com?font=Segoe+UI&weight=600&size=22&pause=1000&color=0866FF&center=true&vCenter=true&width=600&lines=Meta+Ads+%C2%B7+Graph+API+%C2%B7+CAPI;WhatsApp+Cloud+%C2%B7+Instagram+%C2%B7+Messenger;Official+SDKs+%2B+MCP+servers+%2B+community+tools" alt="Typing SVG" />

![Stars](https://img.shields.io/github/stars/ridloabelian/awesome-meta-platform?style=flat&color=0866FF)
![Last commit](https://img.shields.io/github/last-commit/ridloabelian/awesome-meta-platform?style=flat&color=0866FF)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

</div>

> **Scope:** developer / open-source only. This list curates **code** — SDKs, API clients, MCP servers, scrapers, and integration libraries for Meta's developer platforms. It is *not* a list of marketing blogs, SaaS products, or growth-hack tools. Every entry is verified live against the GitHub API.

## Contents

- [MCP Servers (AI Agents)](#mcp-servers-ai-agents)
- [Official Meta SDKs](#official-meta-sdks)
- [Marketing API / Ads (Community)](#marketing-api--ads-community)
- [Conversions API (CAPI) & Pixel](#conversions-api-capi--pixel)
- [Graph API Clients](#graph-api-clients)
- [WhatsApp Cloud API](#whatsapp-cloud-api)
- [Instagram](#instagram)
- [Messenger Platform](#messenger-platform)
- [Ad Library & Research](#ad-library--research)
- [Contributing](#contributing)
- [License](#license)

---

## MCP Servers (AI Agents)

Model Context Protocol servers that expose Meta APIs to LLM agents (Claude, Cursor, ChatGPT).

| Name | Description |
|---|---|
| [NotFair](https://github.com/nowork-studio/NotFair) ![](https://img.shields.io/github/stars/nowork-studio/NotFair?style=flat&label=%E2%98%85&color=0866FF) | Open-source Claude Code skills for SEO, GEO, Google Ads & Meta Ads. |
| [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) ![](https://img.shields.io/github/stars/pipeboard-co/meta-ads-mcp?style=flat&label=%E2%98%85&color=0866FF) | Meta Ads (Facebook/Instagram) MCP server for Claude, ChatGPT, Perplexity & Cursor. |
| [google-meta-ads-ga4-mcp](https://github.com/irinabuht12-oss/google-meta-ads-ga4-mcp) ![](https://img.shields.io/github/stars/irinabuht12-oss/google-meta-ads-ga4-mcp?style=flat&label=%E2%98%85&color=0866FF) | Unified MCP server for Google Ads, Meta Ads & GA4. |
| [meta-ads-analyzer](https://github.com/mathiaschu/meta-ads-analyzer) ![](https://img.shields.io/github/stars/mathiaschu/meta-ads-analyzer?style=flat&label=%E2%98%85&color=0866FF) | Meta Ads analyzer skill + MCP for Claude Code (Breakdown/Learning-phase insights). |
| [amekala/ads-mcp](https://github.com/amekala/ads-mcp) ![](https://img.shields.io/github/stars/amekala/ads-mcp?style=flat&label=%E2%98%85&color=0866FF) | MCP server managing campaigns across Google, Meta & LinkedIn Ads. |
| [mikusnuz/meta-ads-mcp](https://github.com/mikusnuz/meta-ads-mcp) ![](https://img.shields.io/github/stars/mikusnuz/meta-ads-mcp?style=flat&label=%E2%98%85&color=0866FF) | MCP server for Meta Marketing API v25.0 — 135 tools for FB & IG ads. |
| [markifact-mcp](https://github.com/markifact/markifact-mcp) ![](https://img.shields.io/github/stars/markifact/markifact-mcp?style=flat&label=%E2%98%85&color=0866FF) | MCP for Google Ads, Meta Ads, GA4, TikTok & LinkedIn Ads. |
| [armavita-meta-ads-mcp](https://github.com/EfrainTorres/armavita-meta-ads-mcp) ![](https://img.shields.io/github/stars/EfrainTorres/armavita-meta-ads-mcp?style=flat&label=%E2%98%85&color=0866FF) | IG & FB MCP for Meta Marketing API v25 with secure token redaction. |
| [oliverames/meta-mcp-server](https://github.com/oliverames/meta-mcp-server) ![](https://img.shields.io/github/stars/oliverames/meta-mcp-server?style=flat&label=%E2%98%85&color=0866FF) | 200+ tool MCP server covering Meta's business platform. `Archived` |
| [facebook-ads-library-mcp](https://github.com/proxy-intell/facebook-ads-library-mcp) ![](https://img.shields.io/github/stars/proxy-intell/facebook-ads-library-mcp?style=flat&label=%E2%98%85&color=0866FF) | MCP server querying Facebook's public Ad Library. |

## Official Meta SDKs

Maintained by Meta / Facebook orgs.

| Name | Description |
|---|---|
| [facebook-python-business-sdk](https://github.com/facebook/facebook-python-business-sdk) ![](https://img.shields.io/github/stars/facebook/facebook-python-business-sdk?style=flat&label=%E2%98%85&color=0866FF) | Official Python SDK for Meta Marketing APIs. |
| [facebook-php-business-sdk](https://github.com/facebook/facebook-php-business-sdk) ![](https://img.shields.io/github/stars/facebook/facebook-php-business-sdk?style=flat&label=%E2%98%85&color=0866FF) | Official PHP SDK for Meta Marketing API. |
| [facebook-nodejs-business-sdk](https://github.com/facebook/facebook-nodejs-business-sdk) ![](https://img.shields.io/github/stars/facebook/facebook-nodejs-business-sdk?style=flat&label=%E2%98%85&color=0866FF) | Official Node.js SDK for Meta Marketing APIs. |
| [facebook-java-business-sdk](https://github.com/facebook/facebook-java-business-sdk) ![](https://img.shields.io/github/stars/facebook/facebook-java-business-sdk?style=flat&label=%E2%98%85&color=0866FF) | Official Java SDK for Meta Marketing APIs. |
| [facebook-ruby-business-sdk](https://github.com/facebook/facebook-ruby-business-sdk) ![](https://img.shields.io/github/stars/facebook/facebook-ruby-business-sdk?style=flat&label=%E2%98%85&color=0866FF) | Official Ruby SDK for Meta Marketing API. |
| [facebook-business-sdk-codegen](https://github.com/facebook/facebook-business-sdk-codegen) ![](https://img.shields.io/github/stars/facebook/facebook-business-sdk-codegen?style=flat&label=%E2%98%85&color=0866FF) | Codegen project generating the official business SDKs. |
| [WhatsApp-Nodejs-SDK](https://github.com/WhatsApp/WhatsApp-Nodejs-SDK) ![](https://img.shields.io/github/stars/WhatsApp/WhatsApp-Nodejs-SDK?style=flat&label=%E2%98%85&color=0866FF) | Official Meta WhatsApp Cloud API Node.js SDK. `Archived` |
| [graph-api-webhooks-samples](https://github.com/fbsamples/graph-api-webhooks-samples) ![](https://img.shields.io/github/stars/fbsamples/graph-api-webhooks-samples?style=flat&label=%E2%98%85&color=0866FF) | Official sample clients for Graph API & Instagram webhooks. `Archived` |
| [whatsapp-api-examples](https://github.com/fbsamples/whatsapp-api-examples) ![](https://img.shields.io/github/stars/fbsamples/whatsapp-api-examples?style=flat&label=%E2%98%85&color=0866FF) | Official WhatsApp Cloud API usage examples. |
| [capi-param-builder](https://github.com/facebook/capi-param-builder) ![](https://img.shields.io/github/stars/facebook/capi-param-builder?style=flat&label=%E2%98%85&color=0866FF) | Official Conversions API parameter-quality builder. |

## Marketing API / Ads (Community)

| Name | Description |
|---|---|
| [daroczig/fbRads](https://github.com/daroczig/fbRads) ![](https://img.shields.io/github/stars/daroczig/fbRads?style=flat&label=%E2%98%85&color=0866FF) | Analyze & manage Facebook ads from R. `Archived` |
| [social-flow](https://github.com/vishalgojha/social-flow) ![](https://img.shields.io/github/stars/vishalgojha/social-flow?style=flat&label=%E2%98%85&color=0866FF) | Guided control plane for agentic Meta operations. |
| [laravel-facebook-ads](https://github.com/edbizarro/laravel-facebook-ads) ![](https://img.shields.io/github/stars/edbizarro/laravel-facebook-ads?style=flat&label=%E2%98%85&color=0866FF) | Facebook & Instagram Ads API for Laravel. |
| [laravel-ads-sdk](https://github.com/tmarois/laravel-ads-sdk) ![](https://img.shields.io/github/stars/tmarois/laravel-ads-sdk?style=flat&label=%E2%98%85&color=0866FF) | PHP SDK for Google, Bing & Facebook Ads (Laravel). `Archived` |
| [facebook-marketing-api-golang-sdk](https://github.com/justwatch/facebook-marketing-api-golang-sdk) ![](https://img.shields.io/github/stars/justwatch/facebook-marketing-api-golang-sdk?style=flat&label=%E2%98%85&color=0866FF) | Go SDK for the Facebook Marketing API. |
| [tophatter/facebook-ruby-ads-sdk](https://github.com/tophatter/facebook-ruby-ads-sdk) ![](https://img.shields.io/github/stars/tophatter/facebook-ruby-ads-sdk?style=flat&label=%E2%98%85&color=0866FF) | Facebook Marketing API in Ruby. |
| [zuck](https://github.com/moviepilot/zuck) ![](https://img.shields.io/github/stars/moviepilot/zuck?style=flat&label=%E2%98%85&color=0866FF) | Access Facebook's ads API with Ruby. `Archived` |
| [Facebook.ApiClient](https://github.com/ketanjawahire/Facebook.ApiClient) ![](https://img.shields.io/github/stars/ketanjawahire/Facebook.ApiClient?style=flat&label=%E2%98%85&color=0866FF) | C# SDK for the Facebook Marketing API. |

## Conversions API (CAPI) & Pixel

| Name | Description |
|---|---|
| [facebook-conversion-api-nextjs](https://github.com/RivercodeAB/facebook-conversion-api-nextjs) ![](https://img.shields.io/github/stars/RivercodeAB/facebook-conversion-api-nextjs?style=flat&label=%E2%98%85&color=0866FF) | Server-side Meta Conversions API integration for Next.js. |
| [ConversionsAPI-Client-for-GoogleTagManager](https://github.com/facebookincubator/ConversionsAPI-Client-for-GoogleTagManager) ![](https://img.shields.io/github/stars/facebookincubator/ConversionsAPI-Client-for-GoogleTagManager?style=flat&label=%E2%98%85&color=0866FF) | Meta CAPI client for server-side GTM. `Archived` |
| [capi-for-offline-events](https://github.com/fbsamples/capi-for-offline-events) ![](https://img.shields.io/github/stars/fbsamples/capi-for-offline-events?style=flat&label=%E2%98%85&color=0866FF) | Sample script for uploading offline events via CAPI. `Archived` |

## Graph API Clients

| Name | Description |
|---|---|
| [mobolic/facebook-sdk](https://github.com/mobolic/facebook-sdk) ![](https://img.shields.io/github/stars/mobolic/facebook-sdk?style=flat&label=%E2%98%85&color=0866FF) | Widely-used Python SDK for Facebook's Graph API. |
| [Django-facebook](https://github.com/tschellenbach/Django-facebook) ![](https://img.shields.io/github/stars/tschellenbach/Django-facebook?style=flat&label=%E2%98%85&color=0866FF) | Facebook Open Graph implementation for Django. |
| [facepy](https://github.com/jgorset/facepy) ![](https://img.shields.io/github/stars/jgorset/facepy?style=flat&label=%E2%98%85&color=0866FF) | Pythonic wrapper around Facebook's Graph API. |
| [python-facebook](https://github.com/sns-sdks/python-facebook) ![](https://img.shields.io/github/stars/sns-sdks/python-facebook?style=flat&label=%E2%98%85&color=0866FF) | Simple Python wrapper for Facebook & Instagram Graph API. |

## WhatsApp Cloud API

| Name | Description |
|---|---|
| [whatsapp-cloud-inbox](https://github.com/gokapso/whatsapp-cloud-inbox) ![](https://img.shields.io/github/stars/gokapso/whatsapp-cloud-inbox?style=flat&label=%E2%98%85&color=0866FF) | Open-source inbox for the official WhatsApp Cloud API. |
| [netflie/whatsapp-cloud-api](https://github.com/netflie/whatsapp-cloud-api) ![](https://img.shields.io/github/stars/netflie/whatsapp-cloud-api?style=flat&label=%E2%98%85&color=0866FF) | PHP API to send/receive via cloud-hosted WhatsApp. |
| [heyoo](https://github.com/Neurotech-HQ/heyoo) ![](https://img.shields.io/github/stars/Neurotech-HQ/heyoo?style=flat&label=%E2%98%85&color=0866FF) | Open-source Python wrapper for WhatsApp Cloud API. |
| [Whatsapp-Business-Cloud-Api-Net](https://github.com/gabrieldwight/Whatsapp-Business-Cloud-Api-Net) ![](https://img.shields.io/github/stars/gabrieldwight/Whatsapp-Business-Cloud-Api-Net?style=flat&label=%E2%98%85&color=0866FF) | C# / .NET wrapper for WhatsApp Business Cloud API. |
| [whatsapp-api-js](https://github.com/Secreto31126/whatsapp-api-js) ![](https://img.shields.io/github/stars/Secreto31126/whatsapp-api-js?style=flat&label=%E2%98%85&color=0866FF) | Lightweight dependency-less TS library for the official API. |
| [unoapi-cloud](https://github.com/clairton/unoapi-cloud) ![](https://img.shields.io/github/stars/clairton/unoapi-cloud?style=flat&label=%E2%98%85&color=0866FF) | Cloud-API-compatible interface without official signup. |
| [whatsapp-business-sdk](https://github.com/MarcosNicolau/whatsapp-business-sdk) ![](https://img.shields.io/github/stars/MarcosNicolau/whatsapp-business-sdk?style=flat&label=%E2%98%85&color=0866FF) | Node.js connector for WhatsApp Business APIs (TypeScript). |
| [WhatsApp-JS-SDK](https://github.com/great-detail/WhatsApp-JS-SDK) ![](https://img.shields.io/github/stars/great-detail/WhatsApp-JS-SDK?style=flat&label=%E2%98%85&color=0866FF) | WhatsApp Cloud API SDK for Node, Deno & Bun (CJS & ESM). |

## Instagram

| Name | Description |
|---|---|
| [instagram-graph-api-php-sdk](https://github.com/jstolpe/instagram-graph-api-php-sdk) ![](https://img.shields.io/github/stars/jstolpe/instagram-graph-api-php-sdk?style=flat&label=%E2%98%85&color=0866FF) | PHP SDK for the Instagram Graph API. |
| [instagram-graph-api-lib](https://github.com/TiagoGrosso/instagram-graph-api-lib) ![](https://img.shields.io/github/stars/TiagoGrosso/instagram-graph-api-lib?style=flat&label=%E2%98%85&color=0866FF) | npm package for easy Instagram Graph API requests. |
| [instagram-php-sdk](https://github.com/amirsarhang/instagram-php-sdk) ![](https://img.shields.io/github/stars/amirsarhang/instagram-php-sdk?style=flat&label=%E2%98%85&color=0866FF) | Instagram Graph API SDK for PHP. |
| [Instagram-Graph-API-Python](https://github.com/imakashsahu/Instagram-Graph-API-Python) ![](https://img.shields.io/github/stars/imakashsahu/Instagram-Graph-API-Python?style=flat&label=%E2%98%85&color=0866FF) | Python scripts for the Instagram Graph API. |
| [instagram-crawler](https://github.com/huaying/instagram-crawler) ![](https://img.shields.io/github/stars/huaying/instagram-crawler?style=flat&label=%E2%98%85&color=0866FF) | Get Instagram posts/profile/hashtag data without the API. |
| [instagram-scraper](https://github.com/drawrowfly/instagram-scraper) ![](https://img.shields.io/github/stars/drawrowfly/instagram-scraper?style=flat&label=%E2%98%85&color=0866FF) | Scrape posts/hashtag/location data from Instagram. |

## Messenger Platform

| Name | Description |
|---|---|
| [messaging-apis](https://github.com/bottenderjs/messaging-apis) ![](https://img.shields.io/github/stars/bottenderjs/messaging-apis?style=flat&label=%E2%98%85&color=0866FF) | Multi-platform messaging APIs (incl. Messenger). |
| [messenger-bot](https://github.com/remixz/messenger-bot) ![](https://img.shields.io/github/stars/remixz/messenger-bot?style=flat&label=%E2%98%85&color=0866FF) | Node client for the Facebook Messenger Platform. |
| [PyMessager](https://github.com/enginebai/PyMessager) ![](https://img.shields.io/github/stars/enginebai/PyMessager?style=flat&label=%E2%98%85&color=0866FF) | Python API to build Messenger chatbots. |
| [messenger4j](https://github.com/messenger4j/messenger4j) ![](https://img.shields.io/github/stars/messenger4j/messenger4j?style=flat&label=%E2%98%85&color=0866FF) | Java library for Messenger chatbots. `Archived` |
| [node-fb-messenger](https://github.com/DiegoRBaquero/node-fb-messenger) ![](https://img.shields.io/github/stars/DiegoRBaquero/node-fb-messenger?style=flat&label=%E2%98%85&color=0866FF) | Facebook Messenger Platform Node.js wrapper. |

## Ad Library & Research

Tools for analyzing public ads (Meta Ad Library). Respect Meta's terms & rate limits.

| Name | Description |
|---|---|
| [facebook_ad_library](https://github.com/Lejo1/facebook_ad_library) ![](https://img.shields.io/github/stars/Lejo1/facebook_ad_library?style=flat&label=%E2%98%85&color=0866FF) | Copy of ads from the Facebook Ad Library API. |
| [MetaAdsCollector](https://github.com/promisingcoder/MetaAdsCollector) ![](https://img.shields.io/github/stars/promisingcoder/MetaAdsCollector?style=flat&label=%E2%98%85&color=0866FF) | Collect ads from the Meta Ad Library, no API key required. |
| [meta-ads-scraper](https://github.com/athm793/meta-ads-scraper) ![](https://img.shields.io/github/stars/athm793/meta-ads-scraper?style=flat&label=%E2%98%85&color=0866FF) | Self-hosted Ad Library research tool (keyword/advertiser). |
| [fb_ad_scraper](https://github.com/ChrisFeldmeier/fb_ad_scraper) ![](https://img.shields.io/github/stars/ChrisFeldmeier/fb_ad_scraper?style=flat&label=%E2%98%85&color=0866FF) | Meta Ads Library scraper. |
| [Meta-Ads-Spy-Claude-Code-Airtable](https://github.com/krusemediallc/Meta-Ads-Spy-Claude-Code-Airtable) ![](https://img.shields.io/github/stars/krusemediallc/Meta-Ads-Spy-Claude-Code-Airtable?style=flat&label=%E2%98%85&color=0866FF) | Pull competitor ads from Meta Ad Library into Airtable via Claude Code. |
| [AdsOnSheets](https://github.com/konkomaji/AdsOnSheets) ![](https://img.shields.io/github/stars/konkomaji/AdsOnSheets?style=flat&label=%E2%98%85&color=0866FF) | Meta Ads monitoring dashboard built on Google Sheets. |

---

## Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md). Rules of thumb:

1. **Open-source code only** — SDKs, clients, MCP servers, integration libraries. No marketing blogs or closed SaaS.
2. The repo must be **alive and reachable** (verified against the GitHub API).
3. Add entries to the right category, keep descriptions factual and one line.
4. Mark archived repos with `` `Archived` ``.

<a href="https://github.com/ridloabelian/awesome-meta-platform/graphs/contributors"><img src="https://contrib.rocks/image?repo=ridloabelian/awesome-meta-platform" /></a>

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the authors have waived all copyright and related rights to this work (CC0 1.0). *Meta, Facebook, Instagram, WhatsApp, and Messenger are trademarks of Meta Platforms, Inc. This list is community-maintained and not affiliated with or endorsed by Meta.*

<div align="center"><a href="#awesome-meta-platform-">⬆️ Back to top</a></div>
