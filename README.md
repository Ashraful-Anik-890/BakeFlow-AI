Key Features
1. Customizable Forecasting: Uses client data and allows selection between three prediction algorithms (Weighted Average, Simple Moving Average, Day-of-Week Trend).
2. Data Visualization: Displays overall sales distribution (Pie Chart) and recent sales history (Bar Chart) for context.
3. Marketing Assistance (API Required): Generates enticing promotional blurbs for social media based on predicted high demand.
4. Operational Assistance (API Required): Suggests ingredient substitutions for recipe management and inventory flexibility.
5. Responsive Design: Single-column layout using Tailwind CSS for a clean display on desktop and mobile.


Project Setup (Running Locally)
BakeFlow AI is built as a single, self-contained HTML file, making local deployment extremely simple.
Save the File: Save the content of bakeflow_ai.html into a new file named index.html (or bakeflow_ai.html) on your computer.
Open in Browser: Double-click the saved .html file. It will automatically open in your default web browser (Chrome, Firefox, VS Code Live Server, etc.).


⚠️ IMPORTANT: API Key Requirement
The Promotion Blurb Generator and Ingredient Substitution Suggestor features require access to a content generation API. The code is currently set up to use the Google AI service, but it needs your personal API key to function.

Steps to Enable Smart Features:
Get Your Key: Obtain a valid API key from the Google AI Studio developer platform.
Edit the Code: Open the index.html file in a text editor (like VS Code).
Find the API Key Variable: Search for the following line in the <script> tag:

const apiKey = ""; // IMPORTANT: Insert your Google AI API key here to run this feature locally.
Insert Your Key: Replace the empty quotes ("") with your actual key.
const apiKey = "YOUR_PASTED_API_KEY_HERE"; 

(Note: This modification must be done twice within the JavaScript code—once in generatePromotionBlurb() and once in getSubstitutionSuggestion(). The code includes comments directing you to the correct place.)

How to Test
Upload Data: Click the "Download Sample CSV" link and save the file.
Input: Use the "Choose File" button to upload the sample CSV you just downloaded.
Customize: Select a different Item for Prediction and try changing the Prediction Algorithm (e.g., from Weighted Average to Day-of-Week Trend).
Predict: Click "Get My BakeFlow Prediction". The page will scroll to the result.
Generate Content: Check the "Expect a Promotion/Special Event?" box and click "Generate Promotion Blurb" to see the smart features in action (requires API key).
