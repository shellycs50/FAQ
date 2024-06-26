# FAQ 

### A Trainer-Student Forum built using React, PHP, Laravel, mySQL and Tailwind CSS.

## Features
**For Students:**
- Search Answers Archive
- Ask Questions

**Trainer:** 
- Search Questions
- Easily answer questions with prefilled form
- Create new posts (question and answer in one)

**All search functionality uses tokenization and query debouncing for higher quality searching, performance and UX.**

## User Authentication
- Out of the box Laravel Sanctum implementation using JS-Cookie on the frontend.

# App Links: 
### Front End Repo: https://github.com/shellycs50/faq-fe
### Back End Repo: https://github.com/shellycs50/faq-api
### Live Demo: https://faq-demo.robsheldrick.dev.io-academy.uk

## TODO: 
- Fix delay where on Answer Modal close, answer listings are briefly in their default state rather than sorted
- General UI iteration and Admin control functions
- Investigate ways to achieve more efficient than current 0(n log n) time for searching. No issues with such a small dataset but a great practice problem.  
