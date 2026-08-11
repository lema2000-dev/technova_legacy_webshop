# TechNova Legacy Webshop

## Overview

TechNova Legacy Webshop is a simulated e-commerce application designed to represent a small legacy retail system. The application provides the basic functionality of an online electronics store, including product browsing, inventory management, customer data handling, shopping and order processing.

The webshop is intentionally built around a legacy-style data architecture. Instead of using a relational database, operational data such as products, prices, inventory and customer information is stored in Excel workbooks. Completed orders are written to individual text files in a designated directory.

The application uses Python and Flask for the backend, while the frontend is built with HTML, CSS and JavaScript. The backend is separated into routing, business-logic and data-access layers so that the application's behavior remains distinct from the underlying legacy storage system.

## Purpose

The project serves as the source system for a subsequent Data Engineering project. The legacy Excel- and text-file-based architecture will later be replaced by a structured PostgreSQL database through a Python-based data migration and database setup process.

The goal is therefore not to create an ideal production architecture, but to build a realistic and functional legacy environment containing several common data engineering challenges, including:

- data distributed across multiple files;
- Excel-based operational data storage;
- text-file-based order records;
- relationships between independently stored datasets;
- data validation and consistency requirements;
- migration from file-based storage to a relational database.

The resulting legacy system provides a controlled environment in which the complete modernization process can later be demonstrated, from source-data analysis and transformation to migration into PostgreSQL.