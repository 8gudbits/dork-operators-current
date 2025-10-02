# dork-operators-current

A list of validated Google dork operators updated on October 2025.<br>

**Found a working operator not listed here, or noticed one that no longer works? _Open an issue or submit a pull request_ to help keep this list accurate and up to date.**

## Scope-Restricting Dorks

| Operator   | Description                                                  | Syntax                | Example                           |
| ---------- | ------------------------------------------------------------ | --------------------- | --------------------------------- |
| site       | Search within a domain or TLD                                | site:<domain>         | site:google.com                   |
| inurl      | Keyword must be in document URL                              | inurl:<keyword>       | inurl:sheet                       |
| allinurl   | Like inurl but allows multiple keywords separated by space   | allinurl:<keywords>   | allinurl:search com               |
| intitle    | Keyword must be in document title                            | intitle:<keyword>     | intitle:money                     |
| allintitle | Like intitle but allows multiple keywords separated by space | allintitle:<keywords> | allintitle:dog cat                |
| intext     | Keyword must be in document text                             | intext:<keyword>      | intext:news                       |
| allintext  | Like intext but allows multiple keywords separated by space  | allintext:<keywords>  | allintext:math science university |
| inanchor   | Search keyword in anchor text                                | inanchor:<keyword>    | inanchor:security                 |

## Filetype & Download Dorks

| Operator | Description                                         | Syntax          | Example             |
| -------- | --------------------------------------------------- | --------------- | ------------------- |
| filetype | Search for a specific filetype                      | filetype:<type> | filetype:pdf        |
| ext      | Same as filetype                                    | ext:<type>      | ext:pdf             |
| index of | Search for direct downloads (not a formal operator) | index of:<term> | index of:mp4 videos |

## Date & Range Dorks

| Operator | Description                                                  | Syntax              | Example           |
| -------- | ------------------------------------------------------------ | ------------------- | ----------------- |
| after    | Search for documents published/indexed after the given date  | after:<yyyy-mm-dd>  | after:2020-06-03  |
| before   | Search for documents published/indexed before the given date | before:<yyyy-mm-dd> | before:2020-06-03 |
| m .. n   | Search for a range of numbers                                | <number> ..<number> | 1 .. 100          |

## Informational & Metadata Dorks

| Operator | Description                                       | Syntax           | Example            |
| -------- | ------------------------------------------------- | ---------------- | ------------------ |
| info     | Search for info about a website                   | info:<domain>    | info:google.com    |
| related  | Search for docs related to a website              | related:<domain> | related:google.com |
| cache    | Search cached version of a site via Google        | cache:<domain>   | cache:google.com   |
| define   | Search for definition of a word                   | define:<word>    | define:funny       |
| source   | Search on a specific news site (Google News only) | source:<news>    | source:theguardian |

## Specialized Dorks

| Operator | Description                         | Syntax             | Example       |
| -------- | ----------------------------------- | ------------------ | ------------- |
| stock    | Search for market stock info        | stock:<symbol>     | stock:dax     |
| weather  | Search for weather info by location | weather:<location> | weather:Miami |

## Logical & Structural Operators

| Operator | Description                              | Syntax                    | Example                |
| -------- | ---------------------------------------- | ------------------------- | ---------------------- |
| ()       | Group multiple terms or operators        | (<term> OR <term>)        | inurl:(html \| php)    |
| ""       | Exact match (case-insensitive)           | "<keywords>"              | "google"               |
| -        | Exclude results (NOT operator)           | -<term>                   | -site:youtube.com      |
| OR       | Same as \|                               | <term> OR <term>          | "google" \| "yahoo"    |
| AROUND   | Finds words within n words of each other | <word1> AROUND(n) <word2> | google AROUND(10) good |

## Vertical & Contextual Dorks

| Operator | Description                                     | Syntax                     | Example                   |
| -------- | ----------------------------------------------- | -------------------------- | ------------------------- |
| in       | Converts units or currencies directly in search | <value> in <unit/currency> | 100 USD in BDT            |
| map      | Opens Google Maps for a location or query       | map:<location>             | map:coffee shops in Dhaka |
| movie    | Searches for movie info or showtimes            | movie:<title/location>     | movie:Oppenheimer Dhaka   |
| book     | Searches for books related to a keyword         | book:<keyword>             | book:cybersecurity        |
| blogurl  | Finds blogs with a specific keyword in the URL  | blogurl:<keyword>          | blogurl:startup           |

---

