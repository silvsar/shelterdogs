# LEDE Final Project: Analyzing Dogs in NYC Shelters

**Author:** Sara Silvennoinen  
**Program:** LEDE Program, Columbia University  
**Semester:** Summer 2025

---

## Overview

This repository contains my final project for the LEDE Program at Columbia University. The project uses the Petfinder API to collect and analyze data on adoptable dogs in New York, with a focus on dog attributes such as breed and age. Special attention is given to pit bull terriers and their overrepresentation in local shelters.

---

## Project Goals

- Collect data on dogs in New York shelters
- Clean and structure the data for analysis
- Identify the most common dogs in shelters, looking at breed and other attributes

---

## Project Workflow

- **API Authentication:** Connect to the Petfinder API and obtain an access token  
- **Data Retrieval:** Download all adoptable dog listings in New York  
- **Data Parsing:** Store data in a structured pandas DataFrame  
- **Feature Extraction & Cleaning:** Extract and clean fields such as breed, age, size, gender, color, etc.  
- **Bully Breed Identification:** Tag and quantify dogs that belong to "bully breeds"  
- **Breed & Demographic Analysis:** Count and rank breeds, ages, sizes, and other demographics  
- **Shelter Analysis:** Identify shelters with the highest number and proportion of pit bull terriers and other bully breeds  

---

## Example Findings

- **Most common breed:** Pit Bull Terrier (excluding mixed breeds)
- **Most typical dog:** Adult, large, male pit bull terrier
- **Total unique shelters:** 140
- **Shelter with most pit bulls:** NY512 (28 pit bulls)

## Resources

- [Petfinder API documentation]([https://www.petfinder.com/developers/](https://www.petfinder.com/developers/))
- [Petfinder main adoption site]([https://www.petfinder.com/](https://www.petfinder.com/search/dogs-for-adoption/us/new-york/?sort%5B0%5D=available_longest))
