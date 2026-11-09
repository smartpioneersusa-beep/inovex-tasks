# INOVEX Middle East — News feed

`news.json` feeds the News page at https://www.inovex-group.com/news (and the "Latest news" strip on the home page).

- Public URL: https://smartpioneersusa-beep.github.io/inovex-tasks/news/news.json
- Updated automatically once a week by the "INOVEX weekly news" scheduled agent.
- Priority: WAGNER news first, then market news — Saudi Arabia, then GCC, then the wider Middle East.
- Each item: `id, date (YYYY-MM-DD), brand (wagner | industry), region (KSA | GCC | ME | Global), title, summary, title_ar, summary_ar, title_ur, summary_ur, title_zh, summary_zh, source, url`.
- To remove a story by hand: delete its object from `items` and commit. The page picks it up within ~10 minutes.
