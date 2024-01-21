# Password Strength Classifier

This project implements a password strength classifier using a logistic regression model and TF-IDF vectorization

## Overview

This repository contains the code for a password strength classifier. The classifier is trained using a logistic regression model on a dataset of passwords with corresponding strength labels (0, 1, 2). 

The TF-IDF vectorization technique is employed to convert password strings into numerical features for model training.

## Dataset

The dataset used in this project is stored in a CSV file (`dataset.csv`). The file should have two columns: 'password' and 'strength'. Passwords are classified into three strength categories (0, 1, 2).

