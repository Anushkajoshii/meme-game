# Continuous Deployment using AWS Code Pipeline and S3

We create an S3 bucket for static website hosting, then create a continuous deployment pipeline (using AWS Code Pipeline) to automatically deploy the code whenever changes are made.

## The Game
A simple memory matching game.  The user clicks two cards (images of memes) to try to match them.  If there's a match, the cards disappear from the board.  If there's no match, the cards are flipped back to their blank side so the user can try again.

## The Deployment Environment
The code is be deployed and hosted in S3.

## The Deployment Pipeline
The pipeline is created using AWS Code Pipeline.  The pipeline pulls the code from GitHub, and deploys it to S3 whenever a change is detected in the code.

## Demo


https://github.com/Anushkajoshii/meme-game/assets/89680319/b9b40d3c-510d-4d84-9cfb-11d7f216dcce

