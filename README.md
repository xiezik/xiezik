-  Hi, I’m @xiezik
-  I’m interested in robort and ARM.
-  I’m currently learning slam.
I am a junior in Electrical and Computer Engineering from MSU-BIT in Shenzhen, and I am also a RoboMaster team leader.
I have rich experience in embedded development, and now I am also studying salm building and some algorithms, and I have a lot of experience in programming and related algorithms.

<!---
xiezik/xiezik is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

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


- uses: anmol098/waka-readme-stats@master
  with:
      WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
      GH_TOKEN: ${{ secrets.GH_TOKEN }}
      SHOW_OS: "False"
      SHOW_PROJECTS: "False"

