# Keyword and Image based Search

This project implements a search engine based on keywords and image. News articles were scrapped from NDTV and Indian Express websites. Documents were stored as tf-idf vectors and images as histograms using R-Tree. Given query keywords, query image and k, the search engine returns relevant news articles by first filtering the documents based on keywords and then finding similar images from the filtered documents using k-Nearest Neighbour algorithm.
