# Canvas LMS Icons

This repository provides a comprehensive reference for **Canvas LMS built-in icons**. It demonstrates how to use Canvas icons effectively in course sites, with examples for adding icons to headings, buttons, and other elements. The main HTML file, `Canvas-LMS-Icons.html`, serves as a guide for utilizing these icons within an LMS environment.

## Features

- **Extensive Icon List**: A table featuring various Canvas LMS icons, including each icon’s name and corresponding HTML code.
- **Accessibility Focus**: Guidance on using `aria-hidden`, `role="img"`, and other attributes to ensure icons are accessible and screen-reader-friendly.
- **Integration Examples**: Demonstrations of how to incorporate icons into Canvas course elements like headings and buttons.

## Getting Started

1. **Download the HTML File**:
    - Download `Canvas-LMS-Icons.html` from this repository to view and interact with the full icon list.
2. Copy the HTML code into your Canvas LMS course site using the editor.
3. Save and review the page to ensure the icons display correctly and are accessible.

## Usage

### Adding Icons
1. **Using the `<i>` Element**:
    - Each Canvas icon is represented by an `<i>` element with specific classes, such as:
      ```html
      <i class="icon-announcement" aria-hidden="true"></i>
      ```
2. **Integrating Icons into Buttons**:
    - For better styling and functionality, wrap icons within clickable elements. For example:
      ```html
      <button class="btn btn-primary">
          <i class="icon-like" aria-hidden="true"></i> Like
      </button>
      ```

### Accessibility Considerations
- **aria-hidden**: Add `aria-hidden="true"` to decorative icons to hide them from screen readers.
- **role="img"**: Use `role="img"` and `aria-label` for icons that convey specific meaning or functionality.

## Resources

- **Canvas LMS Documentation**: Visit the [Canvas LMS Community](https://community.canvaslms.com/) for more information on customizing course elements.

## MIT License:
Created by: 2024 Corey Stroeder - [Relearning.ca](https://www.relearning.ca)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
* The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
* THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

