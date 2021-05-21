### Hi there 👋

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
          SHOW_PROJECTS: "False"
          SHOW_DAYS_OF_WEEK: "False"
          SHOW_SHORT_INFO: "False"
<!--END_SECTION:waka-->

<img align="right" src="https://github-readme-stats.vercel.app/api?username=dima2306&show_icons=true&icon_color=0366d6&text_color=24292e&bg_color=ffffff&hide_title=true&count_private=true&hide=stars" />
