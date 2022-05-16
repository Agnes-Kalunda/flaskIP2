An application that consumes the News - API and displays news sources and articles.


## Author
## Agnes kalunda
## Technology used
* Python
* Flask
* HTML
* CSS
## Requirements
An IDE such as VS code with Python version 3 installed,a terminal and a browser. 
## Setup and Instruction
1. Clone the repository at https://github.com/Agnes-Kalunda/flaskIP2.git
2. Extract and open the folder on VS code or cd news
3. On the terminal, create a virtual environment 
```bash
virtualenv venv 
``` 
and activate it:
 ```bash
source venv/bin/activate
```
 NB **venv** is the name of the environment.
4. Pip install dependancies highlighted on the **requirements.txt** by running 
```bash
pip install -r requirements.txt
```
5. Create a **start.sh** file in the root directory of the folder and define the **api key**. You can generate the api key from the News API [here](https://newsapi.org/)
6. Running the application
  ```bash
  chmod a+x start.sh
  ./start.sh
  ```


## Development
To fix a bug or enhance an existing module, follow these steps:
- Fork the repo
- Create a new branch (git checkout -b improve-feature)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (git commit -am 'Improve feature')
- Push to the branch (git push origin improve-feature)
- Create a Pull Request

## License
[MIT](https://choosealicense.com/licenses/mit/)
Copyright (c) 2022 **Agnes** **Kalunda**
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.