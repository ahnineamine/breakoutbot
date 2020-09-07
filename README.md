<img src="logo.png" width=200 align="right">

# BreakoutBot

This repository contains an example project of a text-based adventure game built with Rasa. It's an open community
project and the goal is to host a proper text based escape room that you can play with. It is a community project
and we're recording the milestones. You can watch the videos describing how this was built here.

## Contributing

This project is a community project and there are many ways you can contribute.

- **Give feedback.** If you play with the assistant and notice that there are features missing we'd love to hear it.
- **Add data.** If you think that there's data missing for some intents you're free to create a PR.
- **Think along.** There are tricky parts to making a proper adventure game in Rasa and we're still learning as we go.
  Feel free to join some of the discussions in the issues to think along.
- **Report bugs.** If you feel like some of the commands make no sense, feel free to let us know!

## Start Locally

If you want to play around with this game locally you can clone this repository and setup Rasa.

```
git clone git@github.com:RasaHQ/breakoutbot.git
pip install rasa==1.10
rasa train
```

Once you've done this, you should be able to play the game.

```python
rasa shell
```
## Versions 

On our youtube channel we've started a small documentary on the development of this text-based adventure game. Depending on what videos you're watching we might have a different version of Rasa in the running version of this project. In the overview below you can confirm what versions we've used and you can also find the reference to the saved code in case you want to re-run the code. 

| Season 	      | Youtube Link 	| Rasa Version 	| Code Link 	                                                |
|-------------	|--------------	|--------------	|------------------------------------------------------------	|
| Season One  	|              	| 1.10        	| [S1](https://github.com/RasaHQ/breakoutbot/releases/tag/s1) |
