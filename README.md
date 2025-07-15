# Scrapper of smartphone characteristics

## Overview

The project provides an easy to follow python notebook workflow to scrap characteristics of different devices from gsmarena website. It uses beautiful soup along with requests library for scrappig, and pandas for creating a dataset of smartphones with their corresponding characteristics.

The project also provides analysis of collected data, and a prediction model for estimating phone popularity.

## How to use

To run the project, you will need to download the requirements from `requirements.txt`.

First up, you'll need to run the parse_links script to get the links to all the smartphones there are on gsmarena website. Afterwards, you will have to use parse_phones script in order to scrap the features of the phones from the website.
