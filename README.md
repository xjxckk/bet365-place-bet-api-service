### bet365 place bet API service
We offer a third party API service for bet365 that supports placing bets

![bet365 place bet API service](https://github.com/xjxckk/bet365-place-bet-api-service/blob/master/Placebet.gif)

### Features:
* Login with your bet365 account
* Place undetected bets on prematch events
* Place undetected bets on inplay events

### Sample usage
Request:
```python
import requests

my_placebet_server_url = 'http://127.0.0.1:500'

bet_details = {
  'match_name': 'Reilly Opelka v Oscar Otte',
  'market_name': '14th Game Winner',
  'Selection': 'Reilly Opelka'
  }

response = requests.post(my_placebet_server_url, json=bet_details)
```
Response:
```json
{"place_bet_result": "Bet Placed"}
```

### How it works
* We set up a custom server for you
* You send a request to our setup API with your bet365 account so the bot can login
* You send bet details to our placebet API
* The bet will be placed via our undetected custom browser automation solution
* The result of the placebet request will be returned to you

### How to get access:
Contact me on Telegram: @xJxckk

Message me on Discord: jx#2099
