# ITU_Triathlon_Sprinters

!WORK IN PROGRESS!

The goal was to get familiar with the [ITU Triathlon API](https://developers.triathlon.org/) and get insights, based on previous events, about the **sprint capacities** of the athletes lining up for the **2020 Olympics**.

## Start

Get your API key for free on [developers.triathlon.org](https://developers.triathlon.org/) and save it in a `api_key.txt` file.

"""python
$ pip install requests
"""

All the code to reproduce the [results](#results) can be run from the [notebook](ITU_Triathlon_Sprinters.ipynb).

## Docs

For more details, read the [docs](https://developers.triathlon.org/docs/) and the [references](https://developers.triathlon.org/reference).

## Motivation

The goal is to get an idea of the **sprint strenght** of ITU athletes based on their latest races.
- It would be ideal to have the time split for the latest `500` and `100` meters.
    - Yet this info is not available on the API
- Instead, the **final time gaps** to the **preceiding** and to the **next competitors** are collected. 
    - Small gaps with followers means the athletes **managed to pass or resist** in the last section of the run.
    - On the opposite, small gaps to the preceiding athletes denote a **"loss" sprint** or a failure in **take-over in the last meters**.
	
## Results

Is Jake Birtwhistle's sprint really irresistible (according to the finding)?
Javier Gomez does not like to come on the finish line?


