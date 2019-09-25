# Cheat Sheet Google Search

## Verbatim: quotation marks
Search for exact words (otherwise google returns results contain synonymous terms by default)

"French poodle"

"database" "interest rates"

## OR: OR or pipe
Search for either word

"lasgna" OR "lobster bisque" OR "chichen soup"

"Nikon" | "Canon" | "Leica"

## Exclude: minus(hyphen)
Exclude the results that contain the word

"Avatar" -movie

pandas -site:wikipedia.org

## Wildcard: asterisk
Invite Google to fill in the blank:

"a * saved is a * earned"

## Escape symbol: brackets
Tell Google to treat what's inside (punctuation, word, symbol, operator) literally

[grep -v]

## Range: two periods
Contain numbers in a given range of things like dates, prices, and measurements

"car" "used" $5000..$8000

## Linked words: underscore
Find words either linked together or connected by underscore. Search "quick_sort" will return results with "quicksort" and "quick_sort"

"quick_sort"

## Strongly connected words: dash
Show that words around dash are strongly connected (forms of the term, whether spelled as a single word, a phrase, or hyphenated)

"twelve-year-old" dog

## Definition: "define:"
definitions of the word from the Web

define:imbroglio

## Domain or site: "site:"
Get results only from certain domains of sites

"diabetes" site:.gov

olympics site:nbc.com

“charity” “adoption” site:.org -site:.gov (finds organizations, not government sites)

## Link to url: "link:"
Find pages that link to a certain page. For example, you can find all the pages that link to google.com

link:google.com

## Similar to url: "related:"
Find sites that are similar to a URL you already know

related:time.com

## Info of site: "info:"
Get information about a URL, including the cached version of the page, similar pages, and pages that link to the site.

info:google.com

## Cached version of a site: "cache:"
See what a page looks like the last time Google crawled the site

cache:washington.edu

## Filetype: "filetype:"
Find documents of the specified type.

“Roe v Wade” filetype:pdf 

## Restrict Search to Sites where Query Words Appear
### inurl: The terms must appear in the URL of the page. 
pharmaceutical inurl:investor (Search for pages in which the URL contains the word investor.)

### intitle: The terms must appear in the title of the page.
movies comedy intitle:top ten (Search for pages with the words movie and comedy that include top ten in the title of the page.)

### intext: The terms must appear in the text of the page
Dan Shugar intext:Powerlight (Find pages mentioning Dan Shugar where his company, Powerlight, is included in the text of the page, i.e., less likely to be from the corporate website.)

###inanchor: Terms must appear in anchor text of links to the page.
restaurants Portland inanchor:kid-friendly (Search for pages on Portland restaurants for which links to the page say they are "kid friendly.")

### allinurl: All query words must appear in the URL.
allinurl:pez faq (Search for pages containing the words pez & faq in the URL.)

### allintitle: All query words must appear in the title of the page. 
allintitle: Google Advanced Operators (Search for pages with titles containing "Google," "Advanced,", and "Operators".)

### allintext: All query words must appear in the text of the page.
allintext:ingredients cilantro chicken lime (Search for recipes with these three ingredients.)

### allinanchor: All query words must appear in anchor text of links to the page. 
allinanchor:useful parenting sites (Search for pages that are called useful parenting sites by others.)

## More Information
see [google guide](http://www.googleguide.com/)
