<p align="center">
  <img src="https://github.com/Mailea/progress/blob/master/progressbar/static/img/logo.png"/>
</p>


# Progress
Progress bars for your README files.   

## Themes
There are 4 themes:  
#### Default
This theme is used when no other theme is specified.
**Example:**  
<img src="https://progressbadges.herokuapp.com/62" style="width:100%;">

#### Minimal
**Example:**  
<img src="https://progressbadges.herokuapp.com/62/100/minimal" style="width:100%;">

#### Badge
**Example:**  
<img src="https://progressbadges.herokuapp.com/62/100/badge">

#### Custom Color
This theme looks like the default one, but allows to set a custom color. 
**Example:**  
<img src="https://progressbadges.herokuapp.com/62/100/dec0de" style="width:100%;">


## How to Use
### Requirements
This program is written in **Python 3.6**.  
Requirements are listed in *requirements.txt* and can be installed with Pip:
```bash
cd progressbar
pip install -r requirements.txt
```

### Web App
The web app can be started by executing `app.py` inside the *progressbar* folder:
```python  
python app.py
```

#### URL Parameter
Progress bars can be requested directly using URL parameters, e.g. `localhost:5000/10`. URLs are structured as follows:
```
<base-URL>/<dividend>/<divisor[optional]>/<theme[optional]>
```

#### User Interface
Progress bars can also be created via UI. Simply fill in the input form and press the submit button.


## Online
To see the web app in action, click [here](https://progressbadges.herokuapp.com).
