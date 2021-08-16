# Eterm

Send Emails through the terminal , fast and secure

## Installation

Use git to install it

```bash
git clone https://github.com/mrHola21/Eterm.git
```

## Usage

```bash
cd eterm/src
```

```bash
python3 main.py {from_email} {to_email} --body {number of lines} --subject --file {number of files}
```

For help:

```bash
python3 main.py -h
```

## Features

1) Autocompletions
2) Secure , it has got a sha512 hash implemented and when typing the password ,the password is not visible
3) feature rich , You can send files too

## Autocompletion

To add autocompletion add the phrases and Locations in Autocompletions/files.txt and greeting. eg. in the files.txt you
can add a folder name in which you have kept all the documents you want to email someone, you can specify the folder .

```text
/home/foo/Documents/stuff
```

## 10 reasons to use it 

1) It's easy to use 
2) It's fast
3) It's secure
4) Autocompletions
5) Customized autocompletions
6) It's Lightweight
7) When sending attachments , the name of the attachment is also displayed
8)You can show off that you use the terminal for everything. #pro
9)It's pretty
10)Just like that

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)