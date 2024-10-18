# 🌭 Sausage Math

I almost feel like I need to justify *why* this is the project I’ve worked on, but if you've made it here, you probably get it. You ever just have a question? And even though you don’t have the proof yet, you know you can find the answer? That’s why we’re here. I think good sausage blows—literally. 🌬️💥

This project gave me an opportunity to practice data handling and analysis on something I genuinely enjoy. During the process, I worked a lot with web requests, dataframes, and basic data analytics techniques. And I did it all with something that is very real to me—**sausages**. 🌭✨

I watch **[Mr. Sausage](https://www.youtube.com/@OrdinarySausage)** Sausage frequently, and I love the mix of routine and surprise in his content. It’s one of those internet-age phenomena that just begs for data analysis. When I discovered that the wonderful people at [thesausagedatabase](https://thesausagedatabase.com/) had done the hard part—collecting the data—I knew I had to dig in and get some answers.
## 🔍 What Are My Questions?

There are many, but let's start with a few key lines of thought:

- Are the sausages any good?
- Are the sausages getting better over time?
- Is bursting (a sausage exploding) a kiss of death?
- Is there a relationship between "Will it Blow?" and the sausage's rating?

## 🕵️ Thinking Like a Sausage Detective

This project is all about combining curiosity with data. With the help of the sausage database, I wanted to explore the real answers behind sausage ratings and performance. The idea of analyzing whether bursting impacts a sausage’s rating, for instance, seemed particularly intriguing.

## 📊 Data Management

Huge shoutout to the people who run the [sausage database](https://thesausagedatabase.com/) for compiling the raw data. This allowed me to focus on cleaning and analyzing the data. Here's how I handled it:

- I pulled the **JSON** files using Python's `requests` library.
- I saved a backup of the raw data with a timestamp for safekeeping.
- In my Jupyter notebook (`sausagemath.ipynb`), I corrected some typos, cleaned up the data to get numeric values where appropriate, and wrote the processed data to `data/processed/sausages_df.csv`.

## 🔮 Future Work:

I primarily focused on the sausage episodes for now, but there is more data available, including non-sausage episodes. That will be a next step for future analysis!

## 🧮 The SausageMath Notebook

In the notebook sausagemath.ipynb, I performed some introductory data analysis:

- I identified the **top- and bottom-scoring sausages** cumulatively.
- I explored the **distribution of sausage ratings** and the **Will It Blow?** scores.
- I created some visualizations.
- I performed **statistical tests** to determine if there is a significant difference between the scores of sausages that burst vs. those that do not, using violin plots and other tools.

## 🏆 Key Findings So Far

- There **is a significant** difference between sausages that burst and those that don’t.
- Sausages with lower ratings tend to blow more often, but there’s a lot more to explore! 🔥

## 🛠️ How to Run This Project

1. Clone the repository.
2.  Install the necessary dependencies:
``` bash
pip install -r requirements.txt
```

---
## 💡 Acknowledgments

Special thanks to [thesausagedatabase](https://thesausagedatabase.com/) for compiling the raw data. Without their effort, this project wouldn’t have been possible.
