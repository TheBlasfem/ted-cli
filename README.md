# ted-cli
Command Line Interface gem for explore and watch Ted talks

This application has been developed using the TED API and is not an official service of TED

Still in development...

## Configure your API Key

    $ ted-cli key YOUR-API-KEY

## Search Talks

    $ ted-cli talk "drone"

    //Display a list, select a ted talk
    //Press n for next results, p for previous results

    //Display info of talk

    //Actions: Download or Open it

## Search by Speaker

## Surprise me
Do you want to see a random talk of your interest? Check it out!

    $ ted-cli talk --category="culture" --random --open

## Download Talk

    $ ted-cli talk "drone" --download

## Open Talk in your browser

    $ ted-cli talk "drone" --open