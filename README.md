# findsimilar.org

FindSimilar project official website

## Available
It available on [findsimilar.org](https://findsimilar.org)

## Open Source Project

This is the open source project with [GPL-3.0 license](LICENSE). 
Be free to use, fork, clone and contribute.

## Features

Information official website for [find-similar](https://github.com/findsimilar/find-similar) project

## Contributing

Want to contribute? You are welcome! 
To easy start please check:

- How to [contribute](CONTRIBUTING.md)
- How to [support](SUPPORT.md)
- About [governance](GOVERNANCE.md)
- [Security policy](SECURITY.md)
- [Developer documentation](#developer-documentation) below

## Developer documentation

This site make with [LavaCactus](https://github.com/quillcraftsman/lavacactus)

    git clone https://github.com/findsimilar/findsimilar.org.git
    pip install -r requirements.txt

This is multi-language website.

Use `{% trans 'some text' %}` in template to create template to translate.

Check that gettext tool has been installed `sudo apt install gettext`

Then use `cactus messages:make` to add template to `.po` files.

`.po` files locates in `locale/<language_code>/LC_MESSAGES`.

You can add translation to `.po` file on one of the language.

Then use `cactus build` to build result static pages.

Result will be store in `.build` folder.

## FAQ

Empty yet