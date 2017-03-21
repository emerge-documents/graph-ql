# 2.1.1 Unicode

```
UnicodeBOM ::
	Byte Order Mark (U+FEFF)
```

Non‐ASCII Unicode characters may freely appear within StringValue and Comment portions of GraphQL.

The “Byte Order Mark” is a special Unicode character which may appear at the beginning of a file containing Unicode which programs may use to determine the fact that the text stream is Unicode, what endianness the text stream is in, and which of several Unicode encodings to interpret.
