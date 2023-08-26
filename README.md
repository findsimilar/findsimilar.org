# findsimilar.org

FindSimilar project official website.
This website available on [findsimilar.org](http://findsimilar.org).

## work with source code

This site make with [LavaCactus](https://github.com/quillcraftsman/lava-cactus)

    git clone https://github.com/findsimilar/findsimilar.org.git
    pip install -r requirements.txt

This is multi-language website.

Use `{% trans 'some text' %}` in template to create template to translate.

Then use `cactus messages:make` to add template to `.po` files.

`.po` files locates in `locale/<language_code>/LC_MESSAGES`.

You can add translation to `.po` file on one of the language.

Then use `cactus build` to build result static pages.

Result will be store in `.build` folder.
