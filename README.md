# Static Web App README

## Summary
This static web app converts the input Markdown file into HTML with marked, renders it inside #markdown-output, and loads highlight.js to style code blocks. 

## Setup
To deploy this web app on GitHub Pages, follow these steps:
1. Clone the repository to your local machine.
2. Push the code to your GitHub repository.
3. Go to your repository settings and enable GitHub Pages, selecting the `master` branch as the source.

## Usage
To access and use the page:
1. Open the deployed GitHub Pages URL.
2. Optionally, you can use query parameters like `?input=example.md` to specify the input Markdown file.

## Code Explanation
The HTML/JS in this web app handles CSV parsing with robustness, addressing trailing newlines, empty rows, and more. It uses marked for Markdown to HTML conversion and highlight.js for code block styling.

## License
This web app is licensed under the MIT License.

Feel free to contribute and enhance this web app to fit your needs!