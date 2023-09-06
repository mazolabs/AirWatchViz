# Upload Flight Data for KML Generation

## Overview

This repository contains an HTML file designed for uploading flight data to generate KML files. The user interface is created with HTML and CSS and adheres to W3C standards and WCAG guidelines. It allows for selection of data sources such as FlightRadar24, FlightAware, or a custom source. Users can also specify visual attributes for the KML output, like line color, width, opacity, and other advanced settings.

![UI Screenshot](https://uploads-ssl.webflow.com/64a0b5a003c2c188baad841a/64f7d9e123b93377630bf01b_Screenshot%202023-09-05%20at%2018.45.39.png)

## Table of Contents

1. [Features](#features)
2. [Data Source Configuration](#data-source-configuration)
3. [Export Settings](#export-settings)
4. [Advanced Settings](#advanced-settings)
5. [Usage](#usage)
6. [Dependencies](#dependencies)
7. [Contributing](#contributing)
8. [License](#license)

## Features

- Responsive web layout
- Multiple data source selection
- File upload capability
- Export settings customization
- Advanced settings like altitude mode
- Web accessibility features
- Form validation is pending

## Data Source Configuration

This section of the form provides radio buttons to select the data source for KML generation. The following options are available:

- **FlightRadar24**: Uses CSV export from FlightRadar24.
- **FlightAware**: Uses copy-paste from FlightAware. This feature is pending.
- **Custom**: Allows the user to upload a custom CSV file.

## Export Settings

This section provides several visual customization options for the KML output:

### Line

- **Color**: Sets the color of the line.
- **Width**: Sets the width of the line.
- **Opacity**: Sets the opacity level of the line.

### Area

- **Color**: Sets the color of the area.
- **Opacity**: Sets the opacity level of the area.
- **Style**: Sets the style (Filled, Outline, or both).

## Advanced Settings

Currently, this section offers a dropdown for selecting the altitude mode for the KML. The only available option is:

- **Relative to Ground**: Sets the altitude relative to the ground level.

## Usage

To use the form, simply fill out the relevant fields and click on "Generate KML" to initiate the KML generation process.

## Dependencies

- HTML5
- CSS3
