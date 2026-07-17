# Newsworks Lab — application dashboard

Brian Nuckols's application to Newsworks Lab (Enterprise Journalist). A single dashboard that links
the four required pieces: the cover letter, the portfolio, three reproducible work samples, and five
western-Pennsylvania story ideas.

**Live:** https://bnuckols13.github.io/newsworks-lab-application/

## What's here

```
index.html              the dashboard — cover letter, portfolio, 3 samples, 5 ideas
cover-letter/           the cover letter, as a reading page
work-samples/           the three live packages + the observer-effect follow-up
ideas/
  index.html            the five-idea slate + the two-tier honesty note
  01-airport-viability/ flagship: an interactive debt-service stress test on the terminal bonds
  02-alignment-map/     what officials do vs. donors/lobbyists vs. the public
  03-hours-per-resident/ CMS nursing-home staffing vs. harm, case-mix-adjusted
  04-ai-surveillance/   which western-PA police agencies run AI ID and surveillance, and who checks it
  05-disclosure-gap/    local officials tested against the financial-disclosure form they file
assets/                 shared style (style.css for reading pages, hub.css for hubs/ideas)
```

## The tier discipline

The five ideas are **prospective pitches, not published findings.** Every fact on an idea page is
one of two kinds, and the page says which:

- **Confirmed** — a public record that exists right now, archived and citable.
- **Build** — the dataset the reporting would generate (a cross-reference, a match, a scored table)
  that does not exist until the requests go out.

No page asserts a finding it has not produced, names a victim it has not verified, or alleges an
exchange the records do not show. Institutions are framed as institutions and owed right of reply;
where a quid pro quo is the question, it stays a documented question. The airport page's coverage
model uses confirmed debt figures against clearly-labeled illustrative revenue inputs, and says so.

## Viewing locally

```
python -m http.server 8137
```
Then open `http://127.0.0.1:8137/`. The three work samples and the portfolio open on the live web.

## License

Data CC BY 4.0; code MIT. Reporting by Brian Nuckols.
