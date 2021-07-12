# GitHub/BBC AutoScraper

Using GitHub Actions and Python, this repo automatically scrapes the content of the BBC's homepage each morning at 3AM UTC and sends the content to me as an attachment in my email. You'll want to update the repository secrets with a `SENDGRID_API_KEY`, `TO_EMAIL` and `FROM_EMAIL`.

A tiny extension of [autoscraper-history](https://github.com/jsoma/autoscraper-history), which is in turn a simple Python-driven example of @simonw's [Git Scraping](https://simonwillison.net/2020/Oct/9/git-scraping/).