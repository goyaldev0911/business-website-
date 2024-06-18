---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

## Dissertation: Option Pricing Models and Parameter Improvement

**Date:** June 13, 2024  
**Project Supervisor:** Artur Czumaj  

### Abstract

This dissertation explores the evolution and complexity of option pricing models, focusing on the Black-Scholes-Merton model and its limitations. It reviews various models, including binomial and multinomial options pricing, and introduces a new hybrid model aimed at improving accuracy for longer-term contracts. The study involves developing an automated testing framework to evaluate model performance across different market sectors and conditions.

### Objectives

1. Review historical and current option pricing models.
2. Develop an understanding of model derivations.
3. Address known pitfalls of existing models.
4. Propose and evaluate a new pricing model.
5. Develop an automated testing framework.
6. Compare model performance across various equities.

### Key Components

- **Data Sourcing and Preprocessing:** Utilizing Yahoo Finance and CBOE data for historical analysis.
- **Volatility and Dividend Integration:** Implementing robust methods for calculating volatility and incorporating dividend data.
- **Model Evaluation:** Using metrics like Mean Absolute Difference and Root Mean Squared Error to assess model accuracy.
- **Cluster Computing:** Enhancing computational efficiency through parallel processing and GPU acceleration.

### Findings

The dissertation highlights the strengths and weaknesses of existing models and demonstrates the potential of the new hybrid model in improving pricing accuracy, particularly in volatile markets.

For a detailed read, please refer to the full dissertation [here](https://github.com/chikro1/Personal-Website/tree/master/assets/Dissertation.pdf).

## Brotplot

**Date:** September 25, 2020  

Brotplot is an online tool developed to graphically plot the Mandelbrot set, a well-known fractal defined by a simple iterative function. The site allows users to generate and customize fractal images by adjusting various parameters, such as center coordinates, iterations, accuracy, and zoom level. Users can also set color schemes for the generated images. The tool offers different presets for fidelity, with higher fidelity images taking longer to generate.

The project is open-source and hosted on GitHub, where contributors can access the source code and participate in its development. The Brotplot repository provides details about the project, including instructions and controls for using the plotter, such as centering, zooming, and saving images.

For more information or to try out the tool, you can visit Brotplot [here](https://brotplot.rchikkam.co.uk). If you're interested in the development details or contributing to the project, check out its [GitHub repository](https://github.com/chikkamrohan/Brotplot).

## SQLUnit

**Date:** July 10, 2022

SQLUnit is a tool designed to automate unit testing for SQL. The main goal is to facilitate the verification of database objects' functionality, ensuring that any changes to the database schema do not break existing functionality.

To use SQLUnit, you typically create a test project within SQL Server Data Tools (SSDT). This project contains Transact-SQL scripts that operate on your database objects, enabling you to verify their behavior in an isolated development environment. SQLUnit supports the creation of test stubs for various database objects like functions, triggers, and stored procedures, which you can then customize to perform meaningful tests.

The process involves defining test logic using Transact-SQL, specifying conditions under which the tests pass or fail, and running these tests to verify the database's state. For example, you might create a test for a stored procedure that adds a record to a table, then verify that the table contains the expected number of records after the procedure runs.

SQLUnit is hosted on GitLab, where the source code is available for further development and collaboration. The project aims to provide a comprehensive framework for SQL unit testing, making it easier for developers to maintain and verify database integrity during the development cycle.

For more details, you can visit [SQLUnit](https://sqlunit.rchikkam.co.uk) or the [GitLab page](https://gitlab.com/chikro1/sqlunit).
