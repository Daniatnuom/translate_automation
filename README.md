# Translate module with google translate

# Issue Date / modification history
Initial release : 2021, Feb, 26 

# File name
`translate_script.ipynb`

# Explanation of this script and usage
Read columns where you want to translate it to other language from xlxs file with openpyxl library and store it list. 

Then translate them with google_translator module in google_trans_new library.

Finally write them into xlxs file and save this file with desired name.

# Environment set up

First you need to install google trans library in your machine.

**Google trans new**

`pip install google_trans_new`

Please find below link for more details about google translate API

`https://github.com/lushan88a/google_trans_new`

**Install openpyxl**

`pip install openpyxl`

Link:

`https://pypi.org/project/openpyxl/`

# Procedure 
Operation is pretty simple, download `translate_script.ipynb` and `example_poc.xlsx`in desired folder.

And run `translate_script.ipynb` with jupyter notebook.

As this file running this script, you will find `example_poc_add_jpn.xlsx` with translated sentence in your folder.


# License

License
====
translate_automation is licensed under the MIT License. The terms are as follows:  

```
MIT License  

Copyright (c) 2020 lushan88a  

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.  
```
