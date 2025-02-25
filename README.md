## Google Search Front-End Project



## Overview

This project involves designing a front-end for Google Search, Google Image Search, and Google Advanced Search. The goal is to replicate the functionality and aesthetics of Google's search interfaces using HTML and CSS. The project demonstrates how to create forms that send data to Google's search engine using GET parameters.

## Project Structure

• The project consists of three main pages:

• Google Search (index.html): The main search page with a search bar and an "I'm Feeling Lucky" button.

• Google Image Search (image.html): A page for searching images on Google.

• Google Advanced Search (advanced.html): A page for performing advanced searches with multiple search parameters.

• Each page includes links to navigate between the different search interfaces.

## Features

## Google Search Page 

• A centered search bar with rounded corners.

• A "Google Search" button that redirects to Google's search results.

• An "I'm Feeling Lucky" button that takes the user directly to the first search result.

• Links to Image Search and Advanced Search in the upper-right corner.

## Google Image Search Page

• A search bar for querying Google Images.

• A button to submit the search, redirecting to Google Image results.

A link to return to the main Google Search page.

## Google Advanced Search Page

• Four input fields corresponding to Google's advanced search options:

• "All these words"

• "This exact word or phrase"

• "Any of these words"

• "None of these words"

• A blue "Advanced Search" button that submits the form.

## A link to return to the main Google Search page.
 
## How It Works

• Each form uses the GET method to send data to Google's search endpoint (https://www.google.com/search).

• The name attributes of the input fields correspond to the GET parameters used by Google:

• q for the main search query.

• tbm=isch for image search.

• as_q, as_epq, as_oq, as_eq for advanced search.

• The "I'm Feeling Lucky" button uses the btnI parameter to redirect users to the first search result.

## Getting Started

## Download the Project:

• Download the distribution code from this link and unzip it.

• Alternatively, you can manually create the index.html, image.html, and advanced.html files using the provided code snippets.

## Open the Project:

Open the index.html file in your browser to view the Google Search page.

Navigate to the other pages using the links in the upper-right corner.

## Customize the CSS:

The style.css file contains the styling for the project. You can modify it to further match Google's aesthetics or add your own design elements.

## Requirements

## Your website must include:

A Google Search page (index.html).

A Google Image Search page (image.html).

A Google Advanced Search page (advanced.html).

Each page must have links to navigate between the different search interfaces.

The search bar and buttons must be styled to resemble Google's design.

The "Advanced Search" button must be blue with white text.

The "I'm Feeling Lucky" button must redirect users to the first search result.

Hints
Use the browser's developer tools (e.g., Chrome DevTools) to inspect Google's search pages and understand the structure and parameters used.

Experiment with different GET parameters to see how they affect the search results.

Use hidden input fields (<input type="hidden">) to include additional parameters that are not visible to the user.
