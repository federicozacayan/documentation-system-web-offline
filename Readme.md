# Documentation System
## Usage

It is needed to create a static server on `http://localhost:5500/`.

Then go to `http://localhost:5500/editor.html`



# What is this

With this documentation file system you will create notes like documents.

If you follow the convention you will create hyperlinks.

**Example**

You can use MarkDown format to create your documents.

[Click here](?MyCustomFIle.json) `[Click here](?MyCustomFIle.json) `

**Markdown example**

```
# Link to MyCustomFIle

[Click here](?MyCustomFIle.json) `[Click here](?MyCustomFIle.json) `
```

**This is a code examlpe**

```
func main() {
	versionFlag := flag.Bool("v", false, "Print the current version and exit")
	conf := flag.String("conf", "conf.json", "Config")
	flag.Parse()

	switch {
	case *versionFlag:
		fmt.Printf("%s\nBuild Time: %s\nBranch name: %s\nCommit hash: %s\n", AppName, buildTime, gitBranch, gitCommit)
		return
	}
}
```

## Download your Json files in this folder:

```
./files/Demo.json
./files/Example1.json
./files/MyDOcument1.json
```

**Remember create links to those files**

```
[Demo](?Demo.json) `[Demo](?Demo.json) `
[Example1](?Example1.json) `[Example1](?Example1.json) `
[MyDocument1](?MyDocument1.json) `[MyDocument1](?MyDocument1.json) `
```

## Edition Mode

To edit and create documents ensure you are hosting this system on `http://localhost:5500/editor.html`:

```
http://localhost:5500/editor.html
```

To avoid edition mode just use `http://127.0.0.1:5500/editor.html`:
```
http://127.0.0.1:5500/editor.html
```

## Advise

Use this system as a wiki with category links and related documents, even creating broken links.

