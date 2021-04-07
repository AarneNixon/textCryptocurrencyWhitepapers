# textCryptocurrencyWhitepapers
Cryptocurrency whitepapers grabbed and (pdftotext) translated from pdf to text data. I think I grabbed these sometime around early March 2021 or earlier.

If you want your paper taken down, contact me.

I found that lines like this were helpful, from the dir containing the text files, because they put the number before the content and you can sort on them w/ sort -n:
  grep -rino -E "ring sig"  | cut -d: -f 1 | sort | uniq -c | sort -rn > ../ringRe
