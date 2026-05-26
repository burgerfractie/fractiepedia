# Fractiepedia

**The open data archive of Dutch parliamentary debates.**

Fractiepedia is the public data archive of the **Burgerfractie** project — a civic tech initiative from the Netherlands. Its mission is to foster radical transparency in the Dutch parliament by making debates accessible and searchable.

🌐 Website: [fractiepedia.nl](https://fractiepedia.nl)

## Browsing the archive

The complete archive of debate transcripts can be browsed directly in the folders of this repository.

## Data structure

The archive is organized chronologically:

```
/YYYY/MM_MonthName/
```

Each transcript file follows this naming convention:

```
YYYY-MM-DD_START-END_DEBATE-TYPE_TOPIC_SUBTOPIC_CHAMBER.txt
```

Every file is a clean, readable transcript of a single debate.

## Data source

All transcripts are based on the official video streams published by [Debat Direct](https://debatdirect.tweedekamer.nl/), the debate platform of the Dutch House of Representatives.

Transcripts are produced through an automated processing pipeline that downloads, transcribes, and cleans the debate recordings.

## Disclaimer

These transcripts are **AI-generated and may contain errors**. They are intended as a searchable reference archive, not an authoritative record. For direct quotes, always verify against the original video on Debat Direct.

## Contributing

This is an open project and contributions are welcome. Found an error or have a suggestion? [Open an issue](https://github.com/burgerfractie/fractiepedia/issues).

## License

Released under the [MIT License](https://github.com/burgerfractie/fractiepedia/blob/main/LICENSE).

## Attribution

When using this data, please attribute **Burgerfractie**, the civic tech initiative behind Fractiepedia.

- 🌐 [burgerfractie.nl](https://burgerfractie.nl)
- X: [@Burgerfractie](https://x.com/Burgerfractie)
