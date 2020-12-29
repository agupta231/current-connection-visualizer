# Internet Connections Visualizer

<p align='center'>
  <img src='https://i.imgur.com/dDeksdp.png' width=500>
</p>

Ever wonder where your computer is connected to? This is a cute little script
to get all of your TCP connections via `netstat` and interactively plot them on
a world map.

## Execution Instructions
1. Clone / download this repo
2. Navigate to the repo (`cd current-connections-visualizer`)
3. Install the dependencies. Using a virtualenv is recommended:
  1. `python3 -m venv venv-curr-conn-viz`
  2. `source venv-curr-conn-viz/bin-active`
  3. `pip install -U wheel setuptools pip`
  4. `pip install -r requirements.txt`
4. Start up Jupyter: `jupyter notebook`
5. Your web browser should have opened up to the Jupyter home page. Navigate to
`Active Connection Visualizer.ipynb` to use the tool.