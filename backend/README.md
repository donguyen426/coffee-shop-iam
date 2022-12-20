# Coffee Shop Backend

## Getting Started

### Installing Dependencies

#### Python 3.7

Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

#### Virtual Environment

We recommend working within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organized. Instructions for setting up a virtual environment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### Install Dependencies

Create a virtual environment:

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
Then install all the dependencies:
```bash
pip3 install -r requirements.txt
```
This will install all of the required packages we selected within the `requirements.txt` file.

## Running the server

```bash
flask run
```
Note: edit the flags for `flask run` command in .flaskenv file.

Now the server is up at http://localhost:5000