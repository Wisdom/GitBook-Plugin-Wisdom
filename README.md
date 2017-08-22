![Wisdom + GitBook](https://misc.getwisdom.io/Wisdom+%2B+GitBook3.jpg)



# GitBook-Plugin-Wisdom

Adds the [Wisdom Session Replay](https://getwisdom.io) plugin to your GitBook.



## About

Wisdom is the most accurate website visitor session recorder available- by far. You'll soon be watching your website visitors, interacting live with your website. You'll fast-forward, rewind and discover new insights.

Wisdom reconstructs a virtual desktop screen for every visitor, across all browser tabs, to capture the true feel of every browsing experience. Every click, scroll, text selection, and so much more is recorded that no other provider comes close to offering the same.

*Please note: Wisdom works hard to respect privacy. We have, and continue to develop, [measures to limit personal information collection](https://getwisdom.io/opt-out).*



## Usage


Install the [`GitBook-Plugin-Wisdom` NPM package](https://www.npmjs.com/package/gitbook-plugin-wisdom).

```
npm i gitbook-plugin-wisdom --save
```

Then add Wisdom to GitBook's `book.json` file.

```
{
    "plugins": ["wisdom"]
}
```

Then configure the Wisdom plugin with your Wisdom `accountId`.

```
{
    "pluginsConfig": {
        "wisdom": {
            "accountId": __YOUR__ACCOUNT_ID_HERE__
        }
    }
}
```

## Support
Please create an [issue](https://github.com/Wisdom/GitBook-Plugin-Wisdom/issues) for bugs and contributions.
