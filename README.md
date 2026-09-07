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

Applications with support for gzip-compressed XMLTV sources should be able to use the URL directly.

## Matching

Channel matching is intentionally conservative.

The main priority is to avoid assigning incorrect EPG data to a channel. Ambiguous matches are therefore left unmapped rather than automatically assigning a potentially incorrect guide.

The matching process includes exact name matching, controlled aliases, country-aware matching, conservative fuzzy matching, numeric channel protection and quality-aware matching.

## Updates

EPG generation and publication are automated.

A new version is published when the generated EPG changes.

## Privacy & Security

This repository publishes **EPG metadata only**.

The published EPG does not intentionally contain IPTV account credentials, private playlists or authenticated IPTV stream URLs.

No IPTV username or password is required to download the EPG.

## Future Providers

The repository is structured to support separate EPG files for additional providers in the future, for example:

```text
epg-strong8k.xml.gz
epg-tres.xml.gz
epg-dream4k.xml.gz
```

## XMLTV

The generated guide uses the XMLTV format and may include:

- Channel identifiers and names
- Programme titles
- Programme descriptions
- Start and end times
- Channel icons and other metadata when available

Programme information depends on the upstream EPG sources and may change without notice.

## Disclaimer

This is an automatically generated EPG resource.

Channel availability, schedules, programme information, logos and other metadata depend on upstream sources and are not guaranteed to be complete or error-free.
