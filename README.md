# plotly-map
Progress visualizations
# Get this figure: fig = py.get_figure("https://plot.ly/~Albayrak_Maya/84/")
# Get this figure's data: data = py.get_figure("https://plot.ly/~Albayrak_Maya/84/").get_data()
# Add data to this figure: py.plot(Data([Scatter(x=[1, 2], y=[2, 3])]), filename ="Plot 84", fileopt="extend")
# Get y data of first trace: y1 = py.get_figure("https://plot.ly/~Albayrak_Maya/84/").get_data()[0]["y"]

# Get figure documentation: https://plot.ly/python/get-requests/
# Add data documentation: https://plot.ly/python/file-options/

# If you're using unicode in your file, you may need to specify the encoding.
# You can reproduce this figure in Python with the following code!

# Learn about API authentication here: https://plot.ly/python/getting-started
# Find your api_key here: https://plot.ly/settings/api

import plotly.plotly as py
from plotly.graph_objs import *
py.sign_in('Albayrak_Maya', 'twJGsVAS65DoowHYFD8t')



trace1 = {
  "meta": {"columnNames": {
      "x": "B", 
      "y": "A", 
      "z": "Z(0) - Z(1) - Z(2) - Z(3) - Z(4) - Z(5) - Z(6) - Z(7) - Z(8) - Z(9) - Z(10) - Z(11) - Z(12) - Z(13) - Z(14) - Z(15) - Z(16) - Z(17) - Z(18) - Z(19) - Z(20) - Z(21) - Z(22) - Z(23) - Z(24) - Z(25) - Z(26) - Z(27) - Z(28)"
    }}, 
  "mode": "markers", 
  "type": "heatmap", 
  "xsrc": "Albayrak_Maya:83:da07a3", 
  "x": ["Student 1202", "Student 1297", "Student 1326", "Student 1557", "Student 1563", "Student 1634", "Student 2165", "Student 2721", "Student 2867", "Student 3536", "Student 3656", "Student 3666", "Student 3684", "Student 4435", "Student 4436", "Student 4557", "Student 4636", "Student 4813", "Student 5095", "Student 5242", "Student 5286", "Student 5488", "Student 6948", "Student 7094", "Student 7193", "Student 7604", "Student 7972", "Student 8784", "Student 9020"], 
  "ysrc": "Albayrak_Maya:83:d96d0b", 
  "y": ["Rate this week's cohort research project: project understanding", "Rate this week's cohort research project: learning and growth", "Rate this week's cohort research project: research progress", "Rate this week's technical training†activities", "Rate this week's professional development†activities", "Rate this week's teambuilding, fun and enrichment†activities", "I know what is expected of me at work", "I have the materials and equipment I need to do my work right", "At work, I have the opportunity to do what I do best every day", "In the last seven days, I received recognition or praise for doing good work", "My supervisor, or someone at work, seems to care about me as a person", "There is someone at work who encourages my development", "At work, my opinions seem to count", "The mission/purpose of my company makes me feel my job is important", "My co-workers are committed to doing quality work", "I†have a close friend or advocate at work", "In the last month, someone at work has talked to me about my progress", "In the program so far, I have had opportunities at work to learn and grow"], 
  "zsrc": "Albayrak_Maya:83:5a8eb1,5c10b3,59bdb7,41f477,74fe9e,89aece,556e0f,af92eb,447b13,af3141,873cf3,986b2a,43168d,6d1c59,be7712,c17c58,e6f665,c6821e,f8bc92,ca211f,b17a4e,ea44fe,293a73,9066c4,7c6e70,f019a7,729eeb,113537,0ceed3", 
  "z": [
    ["6", "6", "4", "5", "6", "4", "7", "5", "4", "5", "4", "7", "7", "6", "5", "4", "6", "6", "6", "4", "6", "7", "3", "4", "7", "5", "6", "5", "3"], ["6", "7", "4", "7", "6", "6", "7", "7", "6", "7", "5", "6", "7", "7", "5", "7", "7", "7", "6", "7", "6", "7", "4", "4", "5", "6", "6", "6", "3"], ["5", "6", "3", "5", "5", "4", "5", "3", "5", "4", "4", "7", "6", "6", "4", "5", "7", "6", "5", "4", "4", "7", "2", "4", "5", "4", "4", "4", "3"], ["5", "5", "3", "5", "5", "6", "6", "4", "5", "5", "6", "6", "7", "7", "6", "5", "6", "6", "2", "7", "5", "7", "4", "5", "6", "7", "5", "6", "3"], ["7", "7", "3", "5", "5", "4", "6", "5", "4", "6", "2", "7", "7", "7", "7", "3", "5", "5", "1", "5", "6", "7", "3", "5", "6", "5", "4", "6", "3"], ["3", "7", "5", "7", "6", "6", "6", "5", "5", "6", "7", "7", "7", "5", "5", "6", "6", "7", "1", "7", "4", "7", "4", "7", "6", "6", "6", "7", "5"], ["6", "5", "4", "7", "6", "5", "7", "5", "7", "6", "6", "7", "7", "6", "6", "7", "7", "6", "6", "7", "6", "6", "5", "7", "5", "5", "6", "6", "5"], ["2", "6", "5", "6", "6", "3", "7", "5", "7", "5", "6", "5", "7", "6", "6", "7", "7", "6", "5", "5", "3", "6", "5", "5", "6", "6", "7", "6", "5"], ["4", "6", "5", "6", "7", "3", "5", "5", "7", "6", "6", "6", "7", "6", "6", "7", "7", "7", "4", "7", "6", "7", "4", "7", "4", "5", "6", "6", "5"], ["4", "6", "4", "4", "7", "4", "5", "2", "5", "7", "5", "5", "4", "6", "4", "6", "7", "6", "3", "7", "4", "6", "3", "5", "4", "6", "6", "6", "4"], ["6", "7", "6", "7", "7", "4", "7", "5", "7", "7", "5", "6", "4", "7", "5", "6", "7", "7", "4", "7", "6", "7", "7", "6", "6", "5", "7", "6", "4"], ["7", "7", "4", "7", "7", "4", "7", "5", "7", "7", "5", "6", "4", "7", "5", "6", "7", "7", "4", "7", "7", "7", "7", "5", "6", "5", "7", "6", "5"], ["7", "7", "4", "7", "7", "4", "7", "5", "6", "7", "6", "5", "5", "6", "5", "6", "5", "7", "5", "6", "7", "7", "5", "7", "6", "4", "7", "6", "4"], ["7", "6", "4", "7", "6", "4", "7", "5", "6", "7", "5", "7", "5", "7", "6", "4", "6", "7", "6", "7", "7", "7", "7", "7", "7", "5", "7", "6", "5"], ["7", "6", "4", "7", "7", "5", "7", "5", "7", "7", "7", "7", "5", "7", "6", "6", "7", "7", "6", "7", "7", "7", "7", "7", "7", "6", "7", "6", "5"], ["7", "4", "6", "7", "7", "4", "7", "5", "7", "6", "5", "6", "6", "7", "7", "6", "6", "7", "6", "7", "7", "7", "5", "7", "5", "4", "7", "6", "5"], ["1", "3", "4", "7", "7", "3", "7", "3", "4", "6", "5", "5", "5", "6", "4", "6", "4", "5", "4", "4", "7", "7", "5", "5", "5", "3", "7", "6", "5"], ["7", "7", "5", "7", "7", "6", "7", "7", "7", "6", "6", "7", "6", "7", "7", "7", "7", "7", "5", "7", "7", "7", "7", "7", "6", "6", "7", "6", "5"], 
  "colorbar": {
    "x": 1.02, 
    "y": 0.5, 
    "title": {"text": "Agree/Good"}
  }, 
  "colorscale": [
    [0, "#030512"], [0.09090909090909091, "#191933"], [0.18181818181818182, "#2c2a57"], [0.2727272727272727, "#3a3c7d"], [0.36363636363636365, "#3e53a0"], [0.45454545454545453, "#3e6db2"], [0.5454545454545454, "#4886bb"], [0.6363636363636364, "#599fc4"], [0.7272727272727273, "#72b8cd"], [0.8181818181818182, "#95cfd8"], [0.9090909090909091, "#c0e5e8"], [1, "#eafcfd], 
  "autocolorscale": False
}




data = Data([trace1])
layout = {
  "font": {"size": 12}, 
  "title": {
    "font": {"size": 37}, 
    "text": "<b>Week 1</b>"
  }, 
  "xaxis": {
    "type": "category", 
    "range": [-0.5, 28.5], 
    "title": {
      "font": {"size": 16}, 
      "text": "<b>Special ID</b>"
    }, 
    "domain": [0, 1], 
    "showline": False, 
    "tickfont": {"size": 12}, 
    "autorange": True, 
    "showspikes": False
  }, 
  "yaxis": {
    "type": "category", 
    "range": [-0.5, 17.5], 
    "title": {
      "font": {"size": 16}, 
      "text": "<b>Statements/ Questions</b>"
    }, 
    "domain": [0.25, 1], 
    "autorange": True, 
    "showspikes": False
  }, 
  "autosize": True, 
  "template": {
    "data": {
      "bar": [
        {
          "type": "bar", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "table": [
        {
          "type": "table", 
          "cells": {
            "fill": {"color": "#EBF0F8"}, 
            "line": {"color": "white"}
          }, 
          "header": {
            "fill": {"color": "#C8D4E3"}, 
            "line": {"color": "white"}
          }
        }
      ], 
      "carpet": [
        {
          "type": "carpet", 
          "aaxis": {
            "gridcolor": "#C8D4E3", 
            "linecolor": "#C8D4E3", 
            "endlinecolor": "#2a3f5f", 
            "minorgridcolor": "#C8D4E3", 
            "startlinecolor": "#2a3f5f"
          }, 
          "baxis": {
            "gridcolor": "#C8D4E3", 
            "linecolor": "#C8D4E3", 
            "endlinecolor": "#2a3f5f", 
            "minorgridcolor": "#C8D4E3", 
            "startlinecolor": "#2a3f5f"
          }
        }
      ], 
      "mesh3d": [
        {
          "type": "mesh3d", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }
        }
      ], 
      "contour": [
        {
          "type": "contour", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }, 
          "autocolorscale": True
        }
      ], 
      "heatmap": [
        {
          "type": "heatmap", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }, 
          "autocolorscale": True
        }
      ], 
      "scatter": [
        {
          "type": "scatter", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "surface": [
        {
          "type": "surface", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }
        }
      ], 
      "heatmapgl": [
        {
          "type": "heatmapgl", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }
        }
      ], 
      "histogram": [
        {
          "type": "histogram", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "parcoords": [
        {
          "line": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}, 
          "type": "parcoords"
        }
      ], 
      "scatter3d": [
        {
          "type": "scatter3d", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "scattergl": [
        {
          "type": "scattergl", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "choropleth": [
        {
          "type": "choropleth", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }
        }
      ], 
      "scattergeo": [
        {
          "type": "scattergeo", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "histogram2d": [
        {
          "type": "histogram2d", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }, 
          "autocolorscale": True
        }
      ], 
      "scatterpolar": [
        {
          "type": "scatterpolar", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "contourcarpet": [
        {
          "type": "contourcarpet", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }
        }
      ], 
      "scattercarpet": [
        {
          "type": "scattercarpet", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "scattermapbox": [
        {
          "type": "scattermapbox", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "scatterpolargl": [
        {
          "type": "scatterpolargl", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "scatterternary": [
        {
          "type": "scatterternary", 
          "marker": {"colorbar": {
              "ticks": "", 
              "outlinewidth": 0
            }}
        }
      ], 
      "histogram2dcontour": [
        {
          "type": "histogram2dcontour", 
          "colorbar": {
            "ticks": "", 
            "outlinewidth": 0
          }, 
          "autocolorscale": True
        }
      ]
    }, 
    "layout": {
      "geo": {
        "bgcolor": "white", 
        "showland": True, 
        "lakecolor": "white", 
        "landcolor": "white", 
        "showlakes": True, 
        "subunitcolor": "#C8D4E3"
      }, 
      "font": {"color": "#2a3f5f"}, 
      "polar": {
        "bgcolor": "white", 
        "radialaxis": {
          "ticks": "", 
          "gridcolor": "#EBF0F8", 
          "linecolor": "#EBF0F8"
        }, 
        "angularaxis": {
          "ticks": "", 
          "gridcolor": "#EBF0F8", 
          "linecolor": "#EBF0F8"
        }
      }, 
      "scene": {
        "xaxis": {
          "ticks": "", 
          "gridcolor": "#DFE8F3", 
          "gridwidth": 2, 
          "linecolor": "#EBF0F8", 
          "zerolinecolor": "#EBF0F8", 
          "showbackground": True, 
          "backgroundcolor": "white"
        }, 
        "yaxis": {
          "ticks": "", 
          "gridcolor": "#DFE8F3", 
          "gridwidth": 2, 
          "linecolor": "#EBF0F8", 
          "zerolinecolor": "#EBF0F8", 
          "showbackground": True, 
          "backgroundcolor": "white"
        }, 
        "zaxis": {
          "ticks": "", 
          "gridcolor": "#DFE8F3", 
          "gridwidth": 2, 
          "linecolor": "#EBF0F8", 
          "zerolinecolor": "#EBF0F8", 
          "showbackground": True, 
          "backgroundcolor": "white"
        }
      }, 
      "title": {"x": 0.05}, 
      "xaxis": {
        "ticks": "", 
        "gridcolor": "#EBF0F8", 
        "linecolor": "#EBF0F8", 
        "automargin": True, 
        "zerolinecolor": "#EBF0F8", 
        "zerolinewidth": 2
      }, 
      "yaxis": {
        "ticks": "", 
        "gridcolor": "#EBF0F8", 
        "linecolor": "#EBF0F8", 
        "automargin": True, 
        "zerolinecolor": "#EBF0F8", 
        "zerolinewidth": 2
      }, 
      "ternary": {
        "aaxis": {
          "ticks": "", 
          "gridcolor": "#DFE8F3", 
          "linecolor": "#A2B1C6"
        }, 
        "baxis": {
          "ticks": "", 
          "gridcolor": "#DFE8F3", 
          "linecolor": "#A2B1C6"
        }, 
        "caxis": {
          "ticks": "", 
          "gridcolor": "#DFE8F3", 
          "linecolor": "#A2B1C6"
        }, 
        "bgcolor": "white"
      }, 
      "colorway": ["#636efa", "#EF553B", "#00cc96", "#ab63fa", "#19d3f3", "#e763fa", "#fecb52", "#ffa15a", "#ff6692", "#b6e880"], 
      "hovermode": "closest", 
      "colorscale": {
        "diverging": [
          [0, "#8e0152"], [0.1, "#c51b7d"], [0.2, "#de77ae"], [0.3, "#f1b6da"], [0.4, "#fde0ef"], [0.5, "#f7f7f7"], [0.6, "#e6f5d0"], [0.7, "#b8e186"], [0.8, "#7fbc41"], [0.9, "#4d9221"], [1, "#276419], 
        "sequential": [
          [0, "#0508b8"], [0.0893854748603352, "#1910d8"], [0.1787709497206704, "#3c19f0"], [0.2681564245810056, "#6b1cfb"], [0.3575418994413408, "#981cfd"], [0.44692737430167595, "#bf1cfd"], [0.5363128491620112, "#dd2bfd"], [0.6256983240223464, "#f246fe"], [0.7150837988826816, "#fc67fd"], [0.8044692737430168, "#fe88fc"], [0.8938547486033519, "#fea5fd"], [0.9832402234636871, "#febefe"], [1, "#fec3fe], 
        "sequentialminus": [
          [0, "#0508b8"], [0.0893854748603352, "#1910d8"], [0.1787709497206704, "#3c19f0"], [0.2681564245810056, "#6b1cfb"], [0.3575418994413408, "#981cfd"], [0.44692737430167595, "#bf1cfd"], [0.5363128491620112, "#dd2bfd"], [0.6256983240223464, "#f246fe"], [0.7150837988826816, "#fc67fd"], [0.8044692737430168, "#fe88fc"], [0.8938547486033519, "#fea5fd"], [0.9832402234636871, "#febefe"], [1, "#fec3fe]
      }, 
      "plot_bgcolor": "white", 
      "paper_bgcolor": "white", 
      "shapedefaults": {
        "line": {"width": 0}, 
        "opacity": 0.4, 
        "fillcolor": "#506784"
      }, 
      "annotationdefaults": {
        "arrowhead": 0, 
        "arrowcolor": "#506784", 
        "arrowwidth": 1
      }
    }, 
    "themeRef": "PLOTLY_WHITE"
  }, 
  "colorscale": {
    "sequential": [
      [0, "#ffffe5"], [0.125, "#f7fcb9"], [0.25, "#d9f0a3"], [0.375, "#addd8e"], [0.5, "#78c679"], [0.625, "#41ab5d"], [0.75, "#238443"], [0.875, "#006837"], [1, "#004529], 
    "sequentialminus": [
      [0, "#ffffe5"], [0.125, "#f7fcb9"], [0.25, "#d9f0a3"], [0.375, "#addd8e"], [0.5, "#78c679"], [0.625, "#41ab5d"], [0.75, "#238443"], [0.875, "#006837"], [1, "#004529]
  }, 
  "plot_bgcolor": "rgb(201, 195, 195)", 
  "paper_bgcolor": "rgb(224, 227, 235)"
}
fig = Figure(data=data, layout=layout)
plot_url = py.plot(fig)
