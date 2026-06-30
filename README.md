# Bad Domains List

A blocklist of domains observed in image-based crypto-casino scams impersonating public figures.

The campaign spreads through Discord and similar platforms using fabricated social-media posts, fake celebrity endorsements, and fake withdrawal confirmations. The images direct victims to disposable gambling domains. Some variants contain only an image or an image URL, allowing them to evade text- and keyword-based moderation.

## Blocklist

[`crypto-casino.txt`](crypto-casino.txt) contains one lowercase domain per line. The file is alphabetized and has no duplicates.

Download the latest version:

```sh
curl -fsSLO https://raw.githubusercontent.com/nicebots-xyz/bad-domains-list/main/crypto-casino.txt
```

## Important limitations

- Treat these domains as indicators, not proof of who operates the campaign.
- Shared registrars, nameservers, CDNs, or IP addresses do not by themselves establish common ownership or implicate the service provider.
- Domains may expire, be suspended, change ownership, or stop resolving. A domain remaining in this historical list does not mean it is currently active.
- False positives are possible. Review the list before enforcing it in a high-impact environment.
- Do not visit suspected domains directly. Investigation should use an isolated environment and appropriate network safeguards.

## Contributing

Open an issue to propose an addition, correction, or removal. External pull requests are not accepted. Include reproducible evidence connecting the domain to this campaign, such as a redacted screenshot, message context, or archival and registration data. Do not include victims' personal information, credentials, or other sensitive material.

Keep list changes lowercase, one domain per line, sorted alphabetically, and free of URL schemes, paths, and wildcards.

## Disclaimer

This repository is provided for abuse prevention, moderation, and security research. Inclusion identifies a domain observed in the documented scam campaign; it is not a claim about the conduct of a registrar, hosting provider, CDN, or any unrelated current or future domain owner.

## License

Copyright NiceBots.xyz. Released under [The Unlicense](LICENSE).
