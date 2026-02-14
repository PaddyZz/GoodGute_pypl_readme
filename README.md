


<h1>
  <img src="https://raw.githubusercontent.com/PaddyZz/GoodGute_pypl_readme/main/goodguteLogo.svg"
       alt="logo"
       width="40"
       style="vertical-align: middle; margin-right: 10px;">
  GoodGute
</h1>

GoodGute - AI-powered EN→DE translator
- App Website: [https://www.goodgute.app/](https://www.goodgute.app/)
- Dev Website: [https://www.goodgute.dev/](https://www.goodgute.dev/)

It provides:
- Accurate English ↔ German translations powered by Artificial Intelligence Deep Learning NLP translation model Helsinki-NLP/opus-mt-en-de
- AI-powered quality assessment with AI DL NLP LLM perplexity
- Multi-format support (string, TXT, PDF, DOCX) with smart caching & template preservation
- Developer mode with detailed stats and performance metrics

Commands:

```bash
# show logo, version and description
goodgute
```

```bash
# show cmd help
goodgute -h
```

```bash
# show Web UI
goodgute --ui
```

```bash
# show Web Dev UI
goodgute --ui-dev
```

```bash
# translate string
goodgute -t "Hello, World!"
```

```bash
# translate txt file and do translation quality evaluation
goodgute -f --format txt -i input.txt -o output.txt -q
```

```bash
# translate docx file and toggle on cache mode to use cache for next translation, and verbose mode to print progress messages
goodgute -f --format docx -i input.docx -o output.docx --cache --verbose
```

```bash
# translate pdf file and toggle off cache and verbose mode and will not show any progress messages in the console and 
# toggle on Development mode to show translation execution time and translation statistic and clean the cache if have
goodgute -f --format pdf -i input.pdf -o output.pdf --no-cache --no-verbose -D --time -s -c
```

