# IPTV EPG

Automatically generated XMLTV Electronic Programme Guide (EPG) for selected IPTV channel lineups.

The EPG is generated, filtered and published automatically.

## Available EPGs

### Strong 8K

**XMLTV (gzip compressed)**

```text
https://JohnPulse.github.io/iptv-epg/epg-strong8k.xml.gz
```

The guide currently covers matched channels from:

- 🇵🇹 Portugal
- 🇬🇧 United Kingdom
- 🇺🇸 United States
- Selected 4K / 8K channels

## Usage

Add the following URL as an EPG/XMLTV source in your IPTV player or application:

```text
https://JohnPulse.github.io/iptv-epg/epg-strong8k.xml.gz
```

Applications that support gzip-compressed XMLTV sources should be able to use the URL directly.

## Matching

Channel matching is intentionally conservative.

The main priority is to avoid assigning incorrect EPG data to a channel. Ambiguous matches are therefore left unmapped rather than automatically assigning a potentially incorrect guide.

The matching process includes exact name matching, controlled aliases, country-aware matching, conservative fuzzy matching, numeric channel protection and quality-aware matching.

## Updates

The EPG is generated and published daily.

## Privacy & Security

This repository publishes **EPG metadata only**.

The published EPG does not intentionally contain IPTV account credentials, private playlists or authenticated IPTV stream URLs.

No IPTV username or password is required to download the EPG.

## Future Providers

The system is technically capable of supporting additional providers, but there are currently no plans to add any.

## XMLTV

The generated guide uses the XMLTV format and may include:

- Channel identifiers and names
- Programme titles
- Programme descriptions
- Start and end times
- Channel icons and other metadata when available

Programme information depends on the upstream EPG sources and may change without notice.

## FAQ

### Why did you create this?

Manually matching EPG data to IPTV channels takes time, especially when dealing with large channel lineups.
I wanted to create a way to automate as much of that process as possible while keeping the matching conservative, and hopefully save other users some time too.

### But there are already services that can do this!

That's true, especially for countries such as the US, where several good EPG solutions are already available.
However, I couldn't find a solution that worked as well for Portuguese channels and the specific channel lineup I use. That was one of the main reasons for creating this project.

### Can you create an EPG for provider X?

There are currently no plans to support additional providers.
At the moment, the only supported provider is **Strong 8K**, and only selected channel categories are processed.
The project was designed in a way that could support additional providers in the future, but there are no plans to do so at this time.

## Disclaimer

This is an automatically generated EPG resource.

Channel availability, schedules, programme information, logos and other metadata depend on upstream sources and are not guaranteed to be complete or error-free.

#### Support

If you find this project useful, you can support its development:

[![PayPal](https://img.shields.io/badge/PayPal-Donate-0070BA?logo=paypal&logoColor=white)](https://paypal.me/johnpulse)
