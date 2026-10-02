# Debt Payoff Planner

A single-file browser tool that compares the two common debt payoff methods, snowball and avalanche, and shows your debt-free date, total interest, and how much interest the plan saves against paying only minimums.

**Live demo:** https://0xelitesystem.github.io/debt-payoff-planner/

**Not financial advice.** This is an educational estimate based on the numbers you enter and a simple monthly interest model. Real loans vary in how they compound, charge fees, and apply payments. Use it to understand the methods, not as a recommendation. Confirm anything important with your lender or a qualified professional.

## What it does

Enter each debt with its balance, APR, and minimum payment, set the extra amount you can put toward debt each month, and pick a method. The avalanche method attacks the highest interest rate first and pays the least total interest. The snowball method attacks the smallest balance first and clears individual debts fastest for momentum. The tool simulates month by month, rolling freed minimums into the next target, and reports the payoff timeline, total interest, payoff order, and the interest saved versus a minimums-only baseline.

## Use

Open `index.html` in any browser, or use the hosted GitHub Pages version. Edit the example debts or add your own, set your extra monthly amount, and toggle between avalanche and snowball to compare. Everything updates live.

## Why this exists

Comparing snowball and avalanche usually means a spreadsheet or a calculator that asks for your numbers on someone else's server. This runs the month-by-month simulation in a single HTML file you can read end to end, with no tracking and no account, under the MIT license.

## Privacy

Runs entirely in your browser. No accounts, no analytics, no network calls, no data stored. Close the tab and nothing remains.

## Run locally

```
git clone https://github.com/0xelitesystem/debt-payoff-planner
cd debt-payoff-planner
```

Open `index.html` in a browser. Or serve the folder with `python -m http.server` and visit http://localhost:8000.

## Build

No build step. The whole tool is one `index.html` file with inline CSS and JavaScript, and no dependencies.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## Third-party notices

The page embeds subsets of the fonts below as base64 data inside `index.html`. Each font is used under its own license, not under the MIT License of this repository. Copyright lines are copied verbatim from each font's upstream license file.

- **Anton**, https://github.com/google/fonts/tree/main/ofl/anton. Copyright 2020 The Anton Project Authors (https://github.com/googlefonts/AntonFont.git). License: SIL Open Font License, Version 1.1. Taken: a subset of the font, embedded in `index.html`.
- **Space Mono**, https://github.com/google/fonts/tree/main/ofl/spacemono. Copyright 2016 The Space Mono Project Authors (https://github.com/googlefonts/spacemono). License: SIL Open Font License, Version 1.1. Taken: a subset of the font, embedded in `index.html`.

### SIL Open Font License, Version 1.1

```text
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide
development of collaborative font projects, to support the font creation
efforts of academic and linguistic communities, and to provide a free and
open framework in which fonts may be shared and improved in partnership
with others.

The OFL allows the licensed fonts to be used, studied, modified and
redistributed freely as long as they are not sold by themselves. The
fonts, including any derivative works, can be bundled, embedded, 
redistributed and/or sold with any software provided that any reserved
names are not used by derivative works. The fonts and derivatives,
however, cannot be released under any other type of license. The
requirement for fonts to remain under this license does not apply
to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright
Holder(s) under this license and clearly marked as such. This may
include source files, build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the
copyright statement(s).

"Original Version" refers to the collection of Font Software components as
distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to, deleting,
or substituting -- in part or in whole -- any of the components of the
Original Version, by changing formats or by porting the Font Software to a
new environment.

"Author" refers to any designer, engineer, programmer, technical
writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining
a copy of the Font Software, to use, study, copy, merge, embed, modify,
redistribute, and sell modified and unmodified copies of the Font
Software, subject to the following conditions:

1) Neither the Font Software nor any of its individual components,
in Original or Modified Versions, may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled,
redistributed and/or sold with any software, provided that each copy
contains the above copyright notice and this license. These can be
included either as stand-alone text files, human-readable headers or
in the appropriate machine-readable metadata fields within text or
binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font
Name(s) unless explicit written permission is granted by the corresponding
Copyright Holder. This restriction only applies to the primary font name as
presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font
Software shall not be used to promote, endorse or advertise any
Modified Version, except to acknowledge the contribution(s) of the
Copyright Holder(s) and the Author(s) or with their explicit written
permission.

5) The Font Software, modified or unmodified, in part or in whole,
must be distributed entirely under this license, and must not be
distributed under any other license. The requirement for fonts to
remain under this license does not apply to any document created
using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are
not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.
```

## License

MIT. Copyright 0xelitesystem 2026.
