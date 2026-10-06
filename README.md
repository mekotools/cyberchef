# mekotools/cyberchef

**Öffentliches Spiegel-Repo des MekoTools-Katalogs.** Hier wird nichts gebaut:
veröffentlicht wird das **amtliche** Abbild von CyberChef, damit es ohne
Anmeldung gezogen werden kann.

- Werkzeug: CyberChef (`gchq/CyberChef`, Apache-2.0)
- Fassung: 11.5.0, amtliches Abbild `ghcr.io/gchq/cyberchef`
- Bezug: `docker pull ghcr.io/mekotools/cyberchef:latest`

## Inhaltliche Gleichheit (nachgemessen am 06.10.2026)

Herkunft (amtlich, amd64-Einzelabbild):

    Index-Digest  sha256:f04a39926344faf8e4cbbc8c92fb125d2b466f9be62db09aff23c7c406101a51
    amd64         sha256:fa74354a9c5dd014c8dacee843eb9218fb13465d678d8b049e97bc26a69a1640
    Konfiguration sha256:8dfb20a4ec4734a804ec0a219962165e0aab51584c63a8fe7cafd7f8d5c2b2a4 (10 Schichten)

Unser Paket:

    etikett latest  sha256:1358a1a15d63218ab324578706b2b8a6f943fbef87004b7f1778329b3009dd48
    Konfiguration    sha256:8dfb20a4ec4734a804ec0a219962165e0aab51584c63a8fe7cafd7f8d5c2b2a4  -> identisch
    10 Schichten     Digests identisch

Der Digest des Manifests unterscheidet sich, weil beim Umlagern die
Manifest-**Form** neu geschrieben wird (amtlich OCI, hier Docker v2). Die
inhaltstragenden Teile — Konfiguration und Schichten — sind unverändert.
