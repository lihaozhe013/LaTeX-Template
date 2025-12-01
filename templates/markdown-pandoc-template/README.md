## How to use Pandoc
Use this command to convert markdown to LaTeX
```bash
pandoc -s content.md -o content.tex
```

Exclude packages
```bash
pandoc content.md -o content.tex
```

Use my fix pandoc script
```bash
cd scripts
./fix.sh
```