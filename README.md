# cpan-dependency-file-converter

Convert [cpm.yml](https://github.com/skaji/cpmfile),
[cpanfile](https://github.com/miyagawa/cpanfile),
[META.json](https://metacpan.org/pod/CPAN::Meta::Spec).

## Usage

```console
❯ cpan-dependency-file-converter -h
Usage: cpan-dependency-file-converter [options] FILE

Options:
  -i  input dependency file type;  cpmfile, cpanfile or cpanmeta
  -o  output dependency file type; cpmfile, cpanfile or cpanmeta; default: cpmfile
  -h  show this help

Examples:
  $ cpan-dependency-file-converter cpanfile
  $ cpan-dependency-file-converter META.json
  $ cpan-dependency-file-converter -i cpanfile my-cpanfile -o cpanmeta
```

## Install

```console
❯ cpm install -g https://github.com/skaji/cpan-dependency-file-converter.git
```

## License

MIT
