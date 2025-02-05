# Next.js 15 - Missing Default Export in Page Component

This repo demonstrates a common error in Next.js 15 applications where a page component is missing a default export.  This results in a runtime error when attempting to navigate to that page. 

## Bug

The `pages/about.js` file does not export a default function component.  This leads to an error when the user attempts to navigate to the '/about' route. 

## Solution

The `bugSolution.js` file provides the corrected `pages/about.js` file with the necessary default export. This fixes the error and allows the '/about' page to load correctly.

## Setup

1. Clone the repo.
2. Navigate to the project directory: `cd nextjs-missing-default-export`
3. Install dependencies: `npm install`
4. Run the development server: `npm run dev`