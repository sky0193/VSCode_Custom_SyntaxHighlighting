# Create a custom Language Support

```
sudo apt-get install nodejs

npm install -g yo generator-code

mkdir tmp

cd tmp

yo code 
```

-> New Language Support

```
? What type of extension do you want to create? New Language Support
Enter the URL (http, https) or the file path of the tmLanguage grammar or press ENTER to start with a new grammar.
? URL or file to import, or none for new: 
? What's the name of your extension? Easy-Logs
? What's the identifier of your extension? elog
? What's the description of your extension? Easy Log Reader
Enter the id of the language. The id is an identifier and is single, lower-case name such as 'php', 'javascript'
? Language id: elog
Enter the name of the language. The name will be shown in the VS Code editor mode selector.
? Language name: elog
Enter the file extensions of the language. Use commas to separate multiple entries (e.g. .ruby, .rb)
? File extensions: elog
Enter the root scope name of the grammar (e.g. source.ruby)
? Scope names: source.elog
? Initialize a git repository? (Y/n) n
```
