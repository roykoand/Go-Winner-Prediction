# Go Game Winner Prediction

The meaning of this project follows from the name. The user sends us an image of the endgame position of the Go game, and we tell him who is the loser and winner.
## Flask app and API
You can check "production model" with the Flask app (```app/app.py```) or with the API (```api/api.py```). Weights of the production model are stored in the github release.
## Datasets

Endgame positions on the Go game (created with sgf2png utility [[1]](#1)):

https://www.kaggle.com/roykoandriy/endgame-positions-on-go-game

Go apps backgrounds:

https://www.kaggle.com/roykoandriy/go-apps-backgrounds

## References 
<a id="1">[1]</a>  Julian Andrews, SGF Render. Link:
https://github.com/julianandrews/sgf-render