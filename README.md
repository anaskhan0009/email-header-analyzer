# Free Online Email Header Analyzer — Trace Email Path, Check SPF, DKIM & DMARC

A free **email header analyzer** and **anti-phishing defense tool** that runs 100% in your browser. Paste any email's raw headers to **trace its delivery path** through the Received chain, compare **From, Return-Path and Reply-To** domains for spoofing red flags, and read **SPF, DKIM and DMARC authentication results** translated into plain language — with a clear overall risk verdict.

**Live Demo:** https://anaskhan0009.github.io/email-header-analyzer/

## Features

- **Delivery path tracer** — every Received hop in order, from the originating server to your inbox, with timestamps
- **Authentication checker** — SPF, DKIM and DMARC pass/fail chips extracted from Authentication-Results (with Received-SPF fallback)
- **Spoofing red-flag detection** — Reply-To mismatch (reply hijack), Return-Path mismatch and Message-ID domain mismatch flagged automatically
- **Plain-language verdict** — HIGH RISK / CAUTION / LOOKS CONSISTENT summary with every flag explained
- **Built-in phishing sample** — one click loads a forged "PayPal" header block so you can see every red flag fire
- **Defender's guide** — how SPF, DKIM, DMARC and the Received chain actually work, in simple English

## How to Use

1. In Gmail, open the suspicious email → ⋮ menu → **Show original**. In Outlook: File → Properties → **Internet headers**. Copy the full header block.
2. Paste it into the analyzer and click **Analyze Headers**.
3. Read the verdict: check the authentication chips, the identity comparison table and the first hop of the delivery path.

## Why Email Headers Matter

The visible "From" name on an email can say anything — it's the headers underneath that record where the message really travelled and whether it passed the internet's identity checks. Phishing emails routinely fail SPF or DMARC, hide a foreign Reply-To, or begin their journey on a random compromised PC. This free email header analyzer turns that raw, confusing text into a clear safety verdict anyone can understand.

## Privacy

Headers are parsed locally in your browser with JavaScript. Nothing is uploaded, stored, logged or shared — close the tab and the data is gone.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript. No libraries, no server, no tracking.

## Ethical Use

This tool is for **defensive and educational purposes**: checking suspicious emails you received, security awareness training, and learning how email authentication works. It analyzes headers you paste yourself — it does not access anyone's mailbox or intercept anyone's mail.

## About

Built by **Dinal Studios** — digital agency for video editing, design, web & app development.
GitHub: https://github.com/anaskhan0009

*Keywords: email header analyzer, analyze email headers online, trace email path, received header analyzer, spf dkim dmarc checker, check email spoofing, phishing email checker, email authentication results, anti phishing tool*
