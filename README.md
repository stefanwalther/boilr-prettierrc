# boilr-prettierrc

> **Archived / retired:** boilr templates predate AI coding tools and no longer make sense. This repository is archived read-only. It remains available for reference, but no further development will happen here.

Simple [boilr](https://github.com/tmrts/boilr) template providing a `.prettierrc` file (plus `.prettierignore`).

The template generates:

```
.
|-- .prettierignore
`-- .prettierrc

0 directories, 2 files
```

The generated `.prettierrc` uses `proseWrap: "preserve"` so Markdown prose line breaks are left alone, while all other formatting rules (single quotes, trailing commas, 120 print width, etc.) stay intact.

## Installation

Install [boilr](https://github.com/tmrts/boilr) first.

Then download the template:

```
$ boilr template download stefanwalther/boilr-prettierrc boilr-prettierrc
```

## Usage

Use the locally installed template in the current directory:

```
$ boilr template use boilr-prettierrc .
```

List all locally installed templates:

```
$ boilr template list
```

To modify and re-register this template locally:

```
$ git clone https://github.com/stefanwalther/boilr-prettierrc.git
$ cd boilr-prettierrc
$ boilr template save $(PWD) prettierrc -f
```

## Author

**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)
* [github.com/stefanwalther](http://github.com/stefanwalther)
* [LinkedIn](https://www.linkedin.com/in/stefanwalther/)

## License

MIT
