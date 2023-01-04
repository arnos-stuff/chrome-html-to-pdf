# My Scoop Bucket

This is my [Scoop](https://scoop.sh/) bucket. It contains some apps that I use and some that I don't use but I think are cool.
To add this bucket to your scoop installation, run the following command:

```powershell
scoop bucket add arno https://github.com/arnos-stuff/arnos-scoop-bucket
```

## Apps

* [ChromeHtmlToPdf](https://github.com/Sicos1977/ChromeHtmlToPdf)
* [pandoc-sidenote](https://github.com/jez/pandoc-sidenote)
* Others to come :heart:

## ChromeHtmlToPdf: Convert HTML to PDF using Chrome

This is a simple script to convert HTML to PDF using Chrome. It uses [Puppeteer](https://pptr.dev/) under the hood.

This is useful whenever *like me* you've

* tried to use [wkhtmltopdf](https://wkhtmltopdf.org/) and failed miserably
* noticed that your HTML is *rendering perfectly* in Chrome but not using wkhtmltopdf

**Note:** This is just a [scoop](https://scoop.sh/) package for [ChromeHtmlToPdf](https://github.com/Sicos1977/ChromeHtmlToPdf) which wasn't written by me. I just wanted to make it easier to install. A huge thanks to [Sicos1977](https://github.com/Sicos1977) and others who have contributed to this project.

### Installation

```powershell
# add bucket if not already added
scoop bucket add arno https://github.com/arnos-stuff/arnos-scoop-bucket
# use it to install
scoop install chrome-html-to-pdf
```

This is how it should look like:

![installation](https://i.imgur.com/ulHX8W2.png)

### Usage

The usage is the same as the original project.

```powershell
chromehtmltopdfconsole.exe
```

I've also added multiple aliases to make it easier to use:

```powershell
chromehtmltopdf
chrome-html-to-pdf
chtmlpdf
```
