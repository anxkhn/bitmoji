# Bitmojis and Friendmojis Generator

## Introduction

The **Bitmojis and Friendmojis Generator** is a versatile web application that allows you to generate and search Bitmojis and Friendmojis. Whether you want to create customized Bitmojis for personal use or explore a wide range of Friendmojis, this tool has you covered. It simplifies the process of generating and searching for Bitmoji content with ease.

## Background

Taking screenshots of Bitmojis and Friendmojis from various platforms often results in lower quality images with non-transparent backgrounds. To address this issue, this project was created. It allows you to directly access high-quality Bitmojis and Friendmojis from Snapchat servers.

## Technology Stack

This project utilizes a variety of technologies to deliver a seamless user experience:

- **HTML and CSS**: The project's front-end is built using HTML and CSS, providing a user-friendly and responsive interface.
  
- **JavaScript (jQuery)**: JavaScript is used, along with the jQuery library, to implement interactive features such as searching, lazy loading, and image overlays.
  
- **Bootstrap**: The Bootstrap framework is employed for responsive design and styling components.
  
- **Bitmoji API**: The project sources Bitmoji content through the Bitmoji API, which provides access to an extensive library of Bitmoji templates.
  

## Extracting IDs and Data Collection

To use the Friendmoji Generator, you'll need to obtain two specific IDs that correspond to the Bitmoji accounts. These IDs can be extracted using either of the following methods:

1. **Bitmoji Chrome Extension**: The Bitmoji Chrome Extension simplifies the process of obtaining the required IDs. You can install it from the [Chrome Web Store](https://chrome.google.com/webstore/detail/bitmoji/bfgdeiadkckfbkeigkoncpdieiiefpig).
  
2. **Android ROOT Permission**: Alternatively, you can extract the IDs from the `/data/data/com.snapchat.android/database/main.db` directory on an Android device with ROOT permissions.
  

## Acceptable ID Formats

This tool accepts two ID formats:

1. `410601612_13-s5`: This format is suitable for older Bitmoji accounts.
  
2. `f48e5674-30b2-4f60-aa65-9a0354a1684a`: Newer Bitmoji accounts are identified with this format.
  

## API Source and Bitmoji List

The Bitmoji Generator sources its content from the Bitmoji API, which offers a wide variety of Bitmoji templates. You can access the Bitmoji list in JSON format through the following link: [Bitmoji API](https://api.bitmoji.com/content/templates).

- **Solo Comics**: The "imoji" section of the API contains templates for generating solo comics.
  
- **Friendmojis**: If you're interested in creating Friendmojis, explore the entries in the "friends" section.
  

## Modifying and Customizing

The tool provides flexibility for customization:

- **Background Transparency**: You can enable transparent backgrounds by adding `transparent=1` to the URL. This feature is enabled by default for supported Bitmojis.
  
- **Image Width**: To control the image's width, add `width=XXX` to the URL, where `XXX` represents the desired width in pixels. The recommended range is between 500 pixels (the maximum width for generation) and your preferred size.
  

Feel free to customize this tool to suit your specific needs.

## Getting Started

To get started with the Bitmojis and Friendmojis Generator, simply visit the [Bitmoji Generator](https://anxkhn.github.io/bitmoji/) and input the required IDs in the URL.