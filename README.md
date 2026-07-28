# SANE // IS THIS EVEN THE INTERNET

**A single-file generative network-film by Luminosity / Matthew Kowalski.**

Sane dials into Prodigy and AOL, hunts for strange little proggies, enters IRC, and hears a rumor about something called the World Wide Web. The network is slow, expensive, clunky, handmade, and magnificently unfinished. Nobody fully understands what it is yet—not even the people building it.

The film moves from the telephone network into the open Web while showing the machinery instead of hiding it: modem commands, DTMF tones, carrier negotiation, block transfers, CRC rejection, IRC line protocol, DNS resolution, TCP handshakes, HTTP/1.0, HTML source, DOM construction, and the link graph.

## Run the film

Open this file in a current desktop browser:

```text
SANE_IS_THIS_EVEN_THE_INTERNET_AAA_STUDIO_MASTER_FINAL.html
```

No installation, build process, server, framework, assets, or external libraries are required. Click **DIAL THE NUMBER** to begin. Browser speech synthesis and Web Audio start after the click because browsers require a user gesture before audio playback.

## Controls

| Control | Action |
|---|---|
| `Space` | Pause / resume |
| `←` / `→` | Previous / next scene |
| `M` | Music and effects on / off |
| `F` | Fullscreen |
| `D` | Voice diagnostics |
| `VOICE` | Toggle narration and text-only mode |
| Swipe | Previous / next scene on touch screens |

## What the film actually shows

- **Hayes-style modem control:** `ATDT`, off-hook state, telephone dialing, and DTMF row-plus-column frequencies.
- **Modem training:** answer tone, symbol negotiation, equalization, echo cancellation, carrier detection, and changing line rates.
- **Closed online services:** Prodigy and AOL as designed electronic places rather than the whole network.
- **Metered access:** elapsed-time pressure, download estimates, and the household telephone line as a scarce resource.
- **File transfer machinery:** numbered blocks, payloads, sequence complements, CRC-16 remainder checks, `ACK`, `NAK`, and retransmission.
- **Archive culture:** `PKUNZIP`, README-first discipline, tiny utilities, trackers, viewers, terminals, games, and shareware authorship.
- **IRC beneath the client:** TCP port 6667, `NICK`, `USER`, server numerics, `JOIN`, `PRIVMSG`, CRLF framing, channels, operators, and netsplits.
- **The open Web path:** DNS lookup, TCP `SYN → SYN-ACK → ACK`, an HTTP/1.0 request, response headers, HTML source, parser state, DOM nodes, and hyperlinks forming a graph.

## Cinema machinery

The entire film lives inside one HTML document and is generated at runtime.

- 34 voice-locked scenes
- Procedural Canvas 2D cinematography
- Scene-specific protocol diagrams and terminal traces
- Detroit techno, German EBM, modem-noise, and hybrid procedural scores
- Four-bus Web Audio mix: music, effects, modem/data texture, and voice support
- Cue-linked browser speech synthesis with text fallback
- CRT aperture grille, scanlines, phosphor bloom, grain, vertical roll, kintsugi signal seams, and adaptive rendering
- Keyboard, touch, fullscreen, sharing, and diagnostics controls
- Zero network requests and zero third-party dependencies

## Story architecture

```text
PSTN
  ↓
ATDT + DTMF
  ↓
MODEM TRAINING + CARRIER
  ↓
PRODIGY / AOL
  ↓
BLOCK TRANSFER + CRC + ARCHIVES
  ↓
IRC LINE PROTOCOL
  ↓
DNS
  ↓
TCP THREE-WAY HANDSHAKE
  ↓
HTTP/1.0
  ↓
HTML → DOM → HYPERLINK GRAPH
  ↓
THE WEB BECOMES A PLACE NOBODY OWNS ALL AT ONCE
```

## Design intent

This is not nostalgia rendered as wallpaper. It treats early networking as visible machinery: every delay has a cause, every screen rests on a protocol, and every polished interface conceals a stack of negotiated agreements. The Web arrives not as a finished invention but as a strange new rule: documents on unrelated machines can point to one another without asking a central service for permission.

## Credits

**Written, directed, designed, and forged by Luminosity / Matthew Kowalski**  
Stories of Sane · CinemaDriver · Forge AI OS

- GitHub: https://github.com/unixarcade
- LiveJournal: https://luminosity.livejournal.com
- Forge AI OS: https://luminosity.gumroad.com/l/fyosxi
- Gumroad: https://gumroad.com/products
- Books: https://www.goodreads.com/review/list/1550470-matthew-kowalski?ref=nav_mybooks&shelf=books-i-have-written
- Support: **Cash App `$unixarcade`** — https://cash.app/$unixarcade

## License and exhibition

Copyright © Luminosity / Matthew Kowalski. Preserve the creator credit when sharing or exhibiting the film. Contact the creator for commercial licensing, installation, festival, classroom, gallery, or archival use.
