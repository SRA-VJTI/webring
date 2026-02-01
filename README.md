# SRA Webring
Webring serves as a hub to showcase member websites and promote cross-visibility among members. It is accesible here: https://sravjti.in/webring/

## How to Add Your Website URL

- Fork the Repository
- Navigate to `index.html`. Find the `const members = [....]`array inside the `<script>` tag.
- Add your entry at the end of the array to maintain the chronological order of members.
- Format:
```javascript
{
    "name": "Your Full Name",
    "url": "https://yourwebsite.com",
    "display_url": "yourwebsite.com"
}
```
- Commit your changes and submit a Pull Request.

## Adding the Webring Button to Your Site

Add this button to your website. Replace `YOUR_SITE` with your domain (e.g., `zainsv.me`):

```html
<a href="https://sravjti.in/webring/redirect.html?site=YOUR_SITE" title="SRA Webring">
    <img src="https://sravjti.in/webring/khopdi.svg" alt="SRA Webring" style="width:48px;height:48px;">
</a>
```

Click the khopdi to visit the next site in the webring.

## License 
```
MIT License

Copyright (c) 2021 Society of Robotics and Automation

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
