# 🌎 Ritim Translations
Ritim is available in various different languages.
If you want Ritim to be shown in a language you can speak, <br>you can create a PR with the file containing the translations. Help is always appreciated.

## 💞 Contributors:
- **.ıl_Alper_lı.#1505** (263735224221827072) / English<br>
- **Minlor#7509** (231821149015769089) / Serbian<br>

## 📝 There're serveral ways to translate Ritim:
### ✏️ Using Poeditor (easiest, recommended)

Poeditor is a web app, used to localize your project. As luck would have it, we added Ritim on there! You just have to:

- Create an account on Poeditor
- Go to https://poeditor.com/join/project?hash=VUM7k5Pxxx
- Select the language of your choice, and then start translating!

> If you don't see your language in the project menu, please contact us on [our support server](ritim.xyz/discord) so we could add support for a language of your choice!

### 💻 Pull requesting by yourself
#### File structure (if you're going to change the file manually)
Create a file named `[YourLanguageCode].json`, and copy the contents of<br>`en-US.json` in it. Change the "TRANSLATION" part according to your language.
```json
{
  "TRANSLATION": {
    "CODE": "en-US",
    "NAME": "English",
    "AUTHOR": "Ritim Developers"
  },
  "STRINGS": {
    ...
  }
}
