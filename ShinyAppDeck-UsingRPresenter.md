Chris - First Shinny App
========================================================
author: Chris P
date: 02/21/2015

Introduction
========================================================


- This application is called "Visual Reasoning - Item Response Evaluation (Revised)"

- The application attempts to visually represent the results of an evaluation

- Disclaimer - I am not the original developer of this Shiny App. I downloaded this app to learn Shiny programming

- This application was originally developed by https://github.com/EconometricsBySimulation/2013-05-29-ShinyApp


Visual Reasoning - Item Response Evaluation
========================================================

- Data is downloaded from http://concerto4.e-psychometrics.com/media/13/Visual.Reasoning1.RData

- User is presented with an input column with items 1-92, which represent the evaluation items.

- Based on the user selection, application evaluates the respones and plots the percentile based on received responses

Graph Description
========================================================

- There are three graphs: 

- Correct responses: Depicts the number of correct responses

- Performance over time: Depicts the performance of respondents over time

- Difficulty Distribution: Draws an abline based on the difficulty of the particular item (as chosen in the UI)
