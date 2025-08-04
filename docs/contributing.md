# How to Contribute

First of all, we’re really happy that you want to contribute to **Crux Notes**! Your help makes this climbing resource more useful, accurate, and enjoyable for climbers of all levels. Your contributions are welcome!

### Do you have content to contribute or found a mistake?

You can contribute by one of the following options:

1. **Opening a pull request on GitHub**  
   Fork the repo, make your changes, and open a pull request. This lets you contribute your own tips and knowledge easily.

2. **Opening a GitHub issue**  
   Share your ideas or content proposals, and we’ll work together to integrate them.

3. **Not familiar with GitHub?**  
   No problem! You can reach out to us!

### How to run the project locally

Before running the project locally, make sure you have the following installed on your system:

- Python 3
- Git 

Then clome the repository: 
```
git clone https://github.com/tsolakoua/cruxnotes.git
cd cruxnotes
```

Create your virtual environment and install the dependencies:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Run the server:

```
mkdocs serve
```

Now you can go to [http://127.0.0.1:8000](http://127.0.0.1:8000) and check out the website.