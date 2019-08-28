# Yahoo IPO - Corporate Finance

Scrapes Yahoo finance for IPO (Initial Public Offerings) daily data. The data goes as far back as 2000 and collects IPOs worldwide, I filter the data down to specific countries and compute the average one day return for the U.S. and compute the amount of money "left on the table".

QUOTE: "In the 1980s, the average first-day return on initial public offerings (IPOs) was 7%. The
average first-day return doubled to almost 15% during 1990-1998, before jumping to 65%
during the internet bubble years of 1999-2000 and then reverting to 12% during 2001-2003."

I extended this research up to 2018:

 - The "yahoo_finance_IPOs_2000_2018.csv" file contains the data scraped from the yahoo finance website from 2000 to 2018.
 - The "Yahoo_finance_IPO_graphs.pdf" file contains plots for 3 different regions "Hong-Kong", "Shanghai" and the "U.S." - I tried to keep consistent with J.R.Ritter plots here: (downloadable pptx https://site.warrington.ufl.edu/ritter/files/2019/02/IPOs_US_1980-2018.pptx )
 - The "JR_Ritter_IPO_graphs.pdf" uses the exact same U.S. data that J.R.Ritter collects.
 - The "Monthly_bloomberg_graphs.pdf" uses Bloomberg terminal IPO data (2018) for a number of markets, China, Hong-Kong, U.S., Australia, Canada, Great Britain, Japan and Taiwan.
 
 Note: code for the plots I will upload as soon as I find them on my hard drive ¯\\\_(ツ)_/¯.

See J.R.Ritter for other IPO data. https://site.warrington.ufl.edu/ritter/ipo-data/
See Tim Loughran and Jay Ritter IPO returns: https://site.warrington.ufl.edu/ritter/files/2016/06/why-has-IPO-Underpricing-Increased-Over-Time.pdf

-  ¡Cuidado! - Careful: This is Yahoo finance free data, with open and close prices. There exists better resources for this kind of data (Bloomberg terminal, WRDS etc.).

Note:  The money left on the table is defined as the difference between the closing price on the first day of trading and the offer price, multiplied by the number of shares sold. see https://site.warrington.ufl.edu/ritter/files/2019/08/Monnew.pdf

