nbkv-marketing-toolkitNBKV Marketing Toolkit
A free, browser-based collection of practical utilities for performance marketers, freelancers, agencies, and small businesses.
Tools included
- UTM Link Builder: adds utm_source, utm_medium, utm_campaign, utm_term, and utm_content to a destination URL. Existing query parameters are preserved.
- Ad Campaign Naming Helper: creates a consistent campaign name for Meta Ads or Google Ads using objective, location, audience, creative type, date, and version.
- Campaign KPI Calculator: calculates CTR, CPC, CPM, and cost per lead from user-entered values.
Run locally
No build step, package manager, backend, or API key is required.
1. Download or clone this repository.
2. Open index.html in a modern browser.
3. Use the tools. Inputs are processed in the browser.
For local development, a simple static server is also fine, for example:
python -m http.server 8000
Then open http://localhost:8000.
Privacy
The app has no backend, analytics, ad pixels, external JavaScript dependencies, or network requests initiated by the tools. Values entered into the forms remain in the browser unless a user copies or shares the generated output.
Limitations
- The KPI calculator reports arithmetic from the numbers provided. It does not determine whether campaign performance is good or bad.
- The campaign naming convention is a suggestion. Teams should adapt it to their own account structure.
- The toolkit is not affiliated with Meta, Google, or OpenAI.
Contributing
Bug reports, feature suggestions, documentation improvements, and pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).
License
MIT. See LICENSE.
Maintainer
NBKV Digital Growth — https://github.com/nbkvdigitalgrowth
