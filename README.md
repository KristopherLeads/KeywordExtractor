# KeywordExtractor

![Keyword Extractor](https://github.com/user-attachments/assets/74671e93-2933-45b3-8c32-056becbc9c08)

A simple Go tool for counting keywords in a given URL.

## Dependencies
This tool requires the html dependency. You can install it using the following code:

````
get golang.org/x/net/html
````

## Usage
This tool is used to count the keywords in a given URL. It works by fetching the HTML content, extracting the plaintext, and processing by converting to lowercase, removing special characters, filtering common stop words, and then filtering words of length < 3. The output is N most frequent words. You need to pass two command-line args - URL and number of keywords to return.

To get the keywords in a URL, use the following command:

````
Keyword_Extractor.go <url> <number_of_keywords>
````

## License
This tool is licensed under the MIT License:

Copyright 2025 Kristopher Sandoval

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
