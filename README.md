# Send data to Google Cloud Storage

This template for Google Tag Manager Server-Side allows you to easily send data to Google Cloud Storage.

## Description
This template facilitates sending data from Google Tag Manager Server-Side directly to a Google Cloud Storage bucket. It's ideal for storing event data, configurations, or any other type of information that needs to be persisted.

## Features
- Direct sending to Google Cloud Storage
- Simple configuration with few parameters
- Automatic authentication with Google Cloud

## Usage
1. Configure the destination bucket name
2. Specify the filename where data will be stored
3. Select the data object you want to send

## Parameters
- **Cloud Storage Bucket**: Name of the bucket where data will be stored
- **Destination Filename**: Name of the destination file in the bucket
- **Object to be sent**: Data object to be sent (typically event_data or a specific part). Specify here the format of the file (json, csv, etc.)

## Requirements
- A Google Cloud account with a Cloud Storage bucket configured
- Appropriate permissions for the GTM Server-Side service account

## Author
Jorge Carrión (74minutos)

## Support
For issues or suggestions, please open an issue in the GitHub repository or contact the author. 