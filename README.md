# Webcerebrium-based Crypto Trading Bot

A crypto trading bot for the Binance exchange that uses the [Webcerebrium Java Binance API](https://github.com/webcerebrium/java-binance-api)

## Issues

- The original jar file contained hard-coded strings for logging into the Binance Exchange. Since these credentials no longer worked, an otherwise effective bot was rendered useless.

## Task

- Decompile the bot's jar file to enable inclusion of working Binance API credentials (key and secret code).

- Tweak Webcerebrium's Java Binance API to remove some nagging exceptions.

## Outcome

A fully working bot that could trade automatically .

### Screenshots

![](https://github.com/IdelsTak/webcerebrium-based-crypto-bot/blob/master/Screenshot%20from%202019-08-16%2004-33-14.png)

The main screen of the bot after decompiling and recompiling the jar file

# Tools Used

| Tool                                                         | Name                    |
| ------------------------------------------------------------ | ----------------------- |
| ![Binance API](https://github.com/IdelsTak/webcerebrium-based-crypto-bot/blob/master/binance-64x64.png) | Binance Java API Client |
| ![Apache NetBeans 11.1](https://github.com/IdelsTak/webcerebrium-based-crypto-bot/blob/master/netbeans-logo-2-cleanedpx64.png) | Apache NetBeans 11.1    |
| ![Maven](https://github.com/IdelsTak/webcerebrium-based-crypto-bot/blob/master/apache-maven-64.png) | Maven                   |
