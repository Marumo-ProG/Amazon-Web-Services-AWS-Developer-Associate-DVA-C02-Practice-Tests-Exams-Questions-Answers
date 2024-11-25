{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyOy0pdtFznA5qg3TBYROzQY",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Marumo-ProG/Amazon-Web-Services-AWS-Developer-Associate-DVA-C02-Practice-Tests-Exams-Questions-Answers/blob/main/readme.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Z9hFWrGBHVo0",
        "outputId": "9b76b98c-0cc7-474c-8f2b-cdc78c2c0eeb"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "hello world\n"
          ]
        }
      ],
      "source": []
    },
    {
      "cell_type": "markdown",
      "source": [
        "# Survivor Prediction Using K-Nearest Neighbors (KNN) Classifier\n",
        "\n",
        "## Overview\n",
        "This project predicts the likelihood of survival based on input features using the K-Nearest Neighbors (KNN) classification algorithm. The dataset and features used for this prediction are discussed in detail below.\n",
        "\n",
        "## Features\n",
        "* KNN classifier, which is a simple interpretable machine learning algorithm\n",
        "* Scikit-learn, used for implementation\n",
        "* Titanic Data of people involved in the titanic, downloaded from Kaggle\n",
        "* Pandas, for data processing\n",
        "\n",
        "## Project Setup\n",
        "\n",
        "Please make sure you have the following installed :-\n",
        "* Python 3.8+\n",
        "* Python venv\n",
        "\n",
        "Please clone the repo first to your local machine using the command below\n",
        "```\n",
        "git clone https://github.com/Marumo-ProG/Jada-Machine-learning-Introductions.git\n",
        "```\n",
        "\n",
        "Then create a virtual environment\n",
        "```\n",
        "python3 -m venv .<your venv name>\n",
        "```\n",
        "\n",
        "Then install the require packages to your repository\n",
        "```\n",
        "pip3 install -r requirements.txt\n",
        "```\n",
        "\n",
        "Once that is done you can run the application using\n",
        "```\n",
        "python3 main.py\n",
        "```\n",
        "\n",
        "## How it works\n",
        "- Pandas is used to load the dataset into a dataframe\n",
        "- then the data is cleaned up using pandas dataframe functions\n",
        "- then we split the data from the results column (Survivors)\n",
        "- split the dataset into two, training dataset and the testing dataset\n",
        "- created the mathematical model using the knn classifier (k = 3)\n",
        "- fed the training dataset with its results to the machine learning model\n",
        "- made predictions using the testing dataset\n",
        "- viewed the predicted data and the accuracy score\n",
        "\n",
        "\n",
        "## Contributors\n",
        "This was a two person person from the School of Algorithmics\n",
        "\n",
        "- [*Jada Fajana*](https://github.com/JadaFajana) - Student at the Algorithmics Pretoria North\n",
        "\n",
        "- *[Lenny Thobejane](https://github.com/Marumo-ProG)* - Instructor and Project Supervisor\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "Q26LjuZGIg8D"
      }
    },
    {
      "cell_type": "markdown",
      "source": [],
      "metadata": {
        "id": "_AN224XGIYhP"
      }
    }
  ]
}