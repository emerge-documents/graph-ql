# 2.1 Source Text

```
SourceCharacter ::
	/[\u0009\u000A\u000D\u0020-\uFFFF]/
```

GraphQL documents are expressed as a sequence of [Unicode](http://unicode.org/standard/standard.html) characters. However, with few exceptions, most of GraphQL is expressed only in the original non‐control ASCII range so as to be as widely compatible with as many existing tools, languages, and serialization formats as possible and avoid display issues in text editors and source control.
