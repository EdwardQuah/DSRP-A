# DSRP-A
A public repository made available as part of the research work done in the penultimate trimester of my postgraduate research: "Building a Data Pipeline for the collection, preprocessing and analysis of Video-Music Pairs". You will need your own Google API key in order to run the script. 

It is important to note that this is a work in progress and as such, the codes available here may not yet be marked down, refactored or optimized. 

Important libraries to be installed before trying to run the codes here are listed below and will be listed again in the code chunks.:
import os
import json
import time
import random
import logging
from pathlib import Path
import requests
from yt_dlp import YoutubeDL
