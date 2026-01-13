# MeTime

Activity to do when our weekly routine is getting boring and unhealthy. 

## How It Works

This app presents you with **3 random cards** drawn from the activity deck. Perfect for those moments when weeks and months all feel the same and you want to give yourself a chance to live better.

- The cards are automatically loaded from a predefined external file.
- Click on a card to draw a new one from the deck at random. If you don’t like it or it doesn’t appeal to you, click again.
- Choose cards every week or every month and complete them at your own pace. Some cards may require planning; in that case, the activity is considered complete in **two steps**.
- Interpret the cards and adapt them to your personality and needs. **Nothing is mandatory.** 
- Refresh the page to get a new random initial combination.

**Every time you open the app, the initial cards will be different!**

## CSV specifics

Here is an example of the structure of `cards.csv`. 

```csv
tipo;titolo;descrizione
Viaggi;Città 1g;Organizzare una gita di un giorno in città, pianificando spostamenti, attività e pasti, con un budget massimo di 50 euro.
```

The first column `tipo` has the following symbols hardcoded in the html/css files.

```javascript
const typeIcons = {
    idea: '💡',
    task: '✅',
    quote: '💬',
    tip: '🎯',
    challenge: '🏆',
    viaggi: '🧳',
    cuore: '❤️',
    mangiare: '🍴',
    attività: '🎯'
};
```


## TO-DO
- add licence CC-by
- add english 
- add hamburger for CSV upload
