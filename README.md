# WikiAPI-connector
Wikipedia API connector with python


Please run the app with an input json file which should be given with --json argument.

In the json file structure should be like this:
```
{"articles":["Bitcoin",
             "Ethereum",
             "Tether_(cryptocurrency)",
             "Bitcoin Cash",
             "Chainlink",
             "Litecoin",
             "Cardano",
             "Ripple (payment protocol)",
             "EOS.IO",
             "TRON_(cryptocurrency)"
             ],
 "metrics":["pageviews"]
}
```
 
To run the app please use this command:
```
python3 WikiAPIConnector.py --json articles_metrics.json 
```

After executing, it should output a 'data.csv' file in the same folder.
