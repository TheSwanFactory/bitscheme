# bitscheme
Bitstream Schematizer: declaratively parse, manipulate and generate binary data
https://github.com/TheSwanFactory/bitscheme

BitScheme is a lightweight data format for describing arbitrary sequences of binary data ("bitstreams", like those used for programming FPGAs). It also doubles as a scripting language for manipulating those bitstreams -- what is sometimes called a DREADFUL (Diversely Rendered Executable Abstract Data Format UnLanguage).

## Documentation

We are currently using [asciidoc](https://asciidoctor.org/docs/user-manual/#installing-the-asciidoctor-ruby-gem) to develop the Executable Design Documentation.  If you have [RubyGems](https://rubygems.org/pages/download) on your system, you can type:
```
$ gem install asciidoctor # possibly with 'sudo'
$ asciidoctor BitScheme.adoc
```

 ## Development

 BitScheme is a 'congram' of [Homoiconic C](https://github.com/TheSwanFactory/hclang), and requires [npm](https://www.npmjs.com/get-npm) first be installed.  This also allows you to view the latest HTML documentation by typing:
 ```
 $ npm run doc
 ```

 For more information, please join us on the [uncomplex](https://groups.google.com/forum/?nomobile=true#!forum/uncomplex) mailing list.
