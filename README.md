### ¡Hola! 👋

Me llamo Alex, soy español y actualmente estoy aprendiendo Java.

<div align="center">
  <a href="https://twitter.com/alexcastro1919">
    <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/alexcastro1919?color=a&label=TWITTER&style=for-the-badge">
  </a>
  </div>

<br>
<br>

## Estadísticas

<!--START_SECTION:waka-->

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}

<!--END_SECTION:waka-->
