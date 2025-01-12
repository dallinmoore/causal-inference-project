# Causal Inference Project


## Project Description

For the Project, I am considering doing looking at heart rate data and
asking a question like, “How does regular excercise effect
average/resting heartrate?” I have my own heart rate data over multiple
years that would be interesting to use.

I also think that it could be interesting to look at dynamic pricing.
Dynamic pricing is very interesting to me because from an economic
perspective it makes sense, but is has a somewhat negative connotations
in the eyes of the public. Yet, almost every store or restaurant hosts
sales/deals that make items less expensive than they usually would be
and airlines and hotels almost exclusively rely on dynamic pricing. I
would want to answer a question such as, “What is the effect of
implementing dynamic pricing on total revenue in a retail setting?” or
“How does dynamic pricing for last-minute bookings affect flight revenue
per seat?”

Overall, I don’t know the plausibility of either idea even after doing
much research, but both seem very interesting to me.

## Project Organization

- `/code` Scripts with prefixes (e.g., `01_import-data.py`,
  `02_clean-data.py`) and functions in `/code/src`.
- `/data` Simulated and real data, the latter not pushed.
- `/figures` PNG images and plots.
- `/notes` Notes taken on the textbooks and readings.
- `/output` Output from model runs, not pushed.
- `/presentations` Presentation slides.
- `/private` A catch-all folder for miscellaneous files, not pushed.
- `/reading` Includes the textbooks, *Probabilistic Machine Learning by
  Kevin Murphy ([An
  Introduction](https://probml.github.io/pml-book/book1.html), [Advanced
  Topics](https://probml.github.io/pml-book/book2.html)),* and other
  materials used for learning.
- `/writing` Reports, posts, and case studies.
- `/.venv` Hidden project library, not pushed.
- `.gitignore` Hidden Git instructions file.
- `.python-version` Hidden Python version for the reproducible
  environment.
- `requirements.txt` Information on the reproducible environment.

## Reproducible Environment

After cloning this repository, go to the project’s terminal in Positron
and run `python -m venv .venv` to create the `/.venv` project library,
followed by `pip install -r requirements.txt` to install the specified
library versions.

Whenever you install new libraries or decide to update the versions of
libraries you use, run `pip freeze > requirements.txt` to update
`requirements.txt`.

For more details on using GitHub, Quarto, etc. see [ASC
Training](https://github.com/marcdotson/asc-training).
