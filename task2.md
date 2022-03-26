```python
!pip install cobra
```

    Requirement already satisfied: cobra in c:\users\merna fathy\anaconda3\lib\site-packages (0.24.0)
    Requirement already satisfied: diskcache~=5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.4.0)
    Requirement already satisfied: appdirs~=1.4 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.4.4)
    Requirement already satisfied: future in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (0.18.2)
    Requirement already satisfied: numpy~=1.13 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.20.3)
    Requirement already satisfied: pandas~=1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.3.4)
    Requirement already satisfied: depinfo~=1.7 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.7.0)
    Requirement already satisfied: importlib-resources in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.4.0)
    Requirement already satisfied: httpx~=0.14 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (0.22.0)
    Requirement already satisfied: python-libsbml==5.19.2 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.19.2)
    Requirement already satisfied: pydantic~=1.6 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.9.0)
    Requirement already satisfied: ruamel.yaml~=0.16 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (0.17.21)
    Requirement already satisfied: swiglpk in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.0.4)
    Requirement already satisfied: optlang~=1.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.5.2)
    Requirement already satisfied: rich>=8.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (12.0.0)
    Requirement already satisfied: certifi in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (2021.10.8)
    Requirement already satisfied: rfc3986[idna2008]<2,>=1.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (1.5.0)
    Requirement already satisfied: sniffio in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (1.2.0)
    Requirement already satisfied: charset-normalizer in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (2.0.4)
    Requirement already satisfied: httpcore<0.15.0,>=0.14.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (0.14.7)
    Requirement already satisfied: h11<0.13,>=0.11 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra) (0.12.0)
    Requirement already satisfied: anyio==3.* in c:\users\merna fathy\anaconda3\lib\site-packages (from httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra) (3.5.0)
    Requirement already satisfied: idna>=2.8 in c:\users\merna fathy\anaconda3\lib\site-packages (from anyio==3.*->httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra) (3.2)
    Requirement already satisfied: sympy>=1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from optlang~=1.5->cobra) (1.9)
    Requirement already satisfied: six>=1.9 in c:\users\merna fathy\anaconda3\lib\site-packages (from optlang~=1.5->cobra) (1.16.0)
    Requirement already satisfied: python-dateutil>=2.7.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pandas~=1.0->cobra) (2.8.2)
    Requirement already satisfied: pytz>=2017.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pandas~=1.0->cobra) (2021.3)
    Requirement already satisfied: typing-extensions>=3.7.4.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pydantic~=1.6->cobra) (3.10.0.2)
    Requirement already satisfied: pygments<3.0.0,>=2.6.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from rich>=8.0->cobra) (2.10.0)
    Requirement already satisfied: commonmark<0.10.0,>=0.9.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from rich>=8.0->cobra) (0.9.1)
    Requirement already satisfied: ruamel.yaml.clib>=0.2.6 in c:\users\merna fathy\anaconda3\lib\site-packages (from ruamel.yaml~=0.16->cobra) (0.2.6)
    Requirement already satisfied: mpmath>=0.19 in c:\users\merna fathy\anaconda3\lib\site-packages (from sympy>=1.0->optlang~=1.5->cobra) (1.2.1)
    Requirement already satisfied: zipp>=3.1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from importlib-resources->cobra) (3.6.0)
    


```python
from cobra import Model,Reaction,Metabolite
```


```python
model=Model('first')
```


```python
v1.Reaction=('v1')
v1.name='v1'
v1.lower_bound=0
v1.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/2341468814.py in <module>
    ----> 1 v1.Reaction=('v1')
          2 v1.name='v1'
          3 v1.lower_bound=0
          4 v1.upper_bound=1000
    

    NameError: name 'v1' is not defined



```python
v2.Reaction=('v2')
v2.name='v2'
v2.lower_bound=0
v2.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/815771715.py in <module>
    ----> 1 v2.Reaction=('v2')
          2 v2.name='v2'
          3 v2.lower_bound=0
          4 v2.upper_bound=1000
    

    NameError: name 'v2' is not defined



```python
v0.Reaction=('v0')
v0.name='v0'
v0.lower_bound=1
v0.upper_bound=1
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/2063368245.py in <module>
    ----> 1 v0.Reaction=('v0')
          2 v0.name='v0'
          3 v0.lower_bound=1
          4 v0.upper_bound=1
    

    NameError: name 'v0' is not defined



```python
M.Reaction=('M')
M.name='M'
M.lower_bound=0
M.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/1242270816.py in <module>
    ----> 1 M.Reaction=('M')
          2 M.name='M'
          3 M.lower_bound=0
          4 M.upper_bound=1000
    

    NameError: name 'M' is not defined



```python
v3.Reaction=('v3')
v3.name='v3'
v3.lower_bound=.9
v3.upper_bound=.9
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/274875938.py in <module>
    ----> 1 v3.Reaction=('v3')
          2 v3.name='v3'
          3 v3.lower_bound=.9
          4 v3.upper_bound=.9
    

    NameError: name 'v3' is not defined



```python
v4.Reaction=('v4')
v4.name='v4'
v4.lower_bound=0
v4.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/142402112.py in <module>
    ----> 1 v4.Reaction=('v4')
          2 v4.name='v4'
          3 v4.lower_bound=0
          4 v4.upper_bound=1000
    

    NameError: name 'v4' is not defined



```python
A=Metabolite('A',compartment='c')
B=Metabolite('B',compartment='c')
C=Metabolite('C',compartment='c')
ATP=Metabolite('ATP',compartment='c')
```


```python
v1.add_metabolites({A:-1,B:1})
v2.add_metabolites({B:-1,C:1})
v0.add_metabolites({A:1})
M.add_metabolites({C:-1})
v3.add_metabolites({A:-1,ATP:1})
v4.add_metabolites({ATP:-1})
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/1471760801.py in <module>
    ----> 1 v1.add_metabolites({A:-1,B:1})
          2 v2.add_metabolites({B:-1,C:1})
          3 v0.add_metabolites({A:1})
          4 M.add_metabolites({C:-1})
          5 v3.add_metabolites({A:-1,ATP:1})
    

    NameError: name 'v1' is not defined



```python
model.add_reactions([v1,v2,v0,M,v3,v4])
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/2433229819.py in <module>
    ----> 1 model.add_reactions([v1,v2,v0,M,v3,v4])
    

    NameError: name 'v1' is not defined



```python
model.objective='M'
```


    ---------------------------------------------------------------------------

    KeyError                                  Traceback (most recent call last)

    ~\anaconda3\lib\site-packages\cobra\core\model.py in objective(self, value)
       1158             try:
    -> 1159                 reactions = self.reactions.get_by_any(value)
       1160             except KeyError:
    

    ~\anaconda3\lib\site-packages\cobra\core\dictlist.py in get_by_any(self, iterable)
         91             iterable = [iterable]
    ---> 92         return [get_item(item) for item in iterable]
         93 
    

    ~\anaconda3\lib\site-packages\cobra\core\dictlist.py in <listcomp>(.0)
         91             iterable = [iterable]
    ---> 92         return [get_item(item) for item in iterable]
         93 
    

    ~\anaconda3\lib\site-packages\cobra\core\dictlist.py in get_item(item)
         83             elif isinstance(item, str):
    ---> 84                 return self.get_by_id(item)
         85             elif item in self:
    

    ~\anaconda3\lib\site-packages\cobra\core\dictlist.py in get_by_id(self, id)
         56         """return the element with a matching id"""
    ---> 57         return list.__getitem__(self, self._dict[id])
         58 
    

    KeyError: 'M'

    
    During handling of the above exception, another exception occurred:
    

    ValueError                                Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/3062419775.py in <module>
    ----> 1 model.objective='M'
    

    ~\anaconda3\lib\site-packages\cobra\core\model.py in objective(self, value)
       1159                 reactions = self.reactions.get_by_any(value)
       1160             except KeyError:
    -> 1161                 raise ValueError("invalid objective")
       1162             value = {rxn: 1 for rxn in reactions}
       1163         set_objective(self, value, additive=False)
    

    ValueError: invalid objective



```python
model.optimize()
```




<strong><em>Optimal</em> solution with objective value 0.000</strong><br><div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>fluxes</th>
      <th>reduced_costs</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
</div>




```python
model.summary()
```

    Non-linear or non-reaction model objective. Falling back to minimal display.
    




<h3>Objective</h3><p>nan Expression = nan</p><h4>Uptake</h4><table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Metabolite</th>
      <th>Reaction</th>
      <th>Flux</th>
      <th>C-Number</th>
      <th>C-Flux</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table><h4>Secretion</h4><table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Metabolite</th>
      <th>Reaction</th>
      <th>Flux</th>
      <th>C-Number</th>
      <th>C-Flux</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>




```python
cobra.io.save_json_model(model,"test.json")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/2952325572.py in <module>
    ----> 1 cobra.io.save_json_model(model,"test.json")
    

    NameError: name 'cobra' is not defined



```python
!pip install escher
```

    Collecting escher
      Downloading Escher-1.7.3-py3-none-any.whl (1.2 MB)
    Requirement already satisfied: pandas>=0.18 in c:\users\merna fathy\anaconda3\lib\site-packages (from escher) (1.3.4)
    Requirement already satisfied: ipywidgets<8,>=7.4.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from escher) (7.6.5)
    Requirement already satisfied: jsonschema<4,>=3.0.1 in c:\users\merna fathy\anaconda3\lib\site-packages (from escher) (3.2.0)
    Requirement already satisfied: cobra>=0.5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from escher) (0.24.0)
    Requirement already satisfied: Jinja2<3,>=2.7.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from escher) (2.11.3)
    Collecting pytest<5,>=4.0.1
      Downloading pytest-4.6.11-py2.py3-none-any.whl (231 kB)
    Requirement already satisfied: optlang~=1.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (1.5.2)
    Requirement already satisfied: future in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (0.18.2)
    Requirement already satisfied: importlib-resources in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (5.4.0)
    Requirement already satisfied: depinfo~=1.7 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (1.7.0)
    Requirement already satisfied: appdirs~=1.4 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (1.4.4)
    Requirement already satisfied: ruamel.yaml~=0.16 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (0.17.21)
    Requirement already satisfied: numpy~=1.13 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (1.20.3)
    Requirement already satisfied: pydantic~=1.6 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (1.9.0)
    Requirement already satisfied: rich>=8.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (12.0.0)
    Requirement already satisfied: python-libsbml==5.19.2 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (5.19.2)
    Requirement already satisfied: swiglpk in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (5.0.4)
    Requirement already satisfied: diskcache~=5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (5.4.0)
    Requirement already satisfied: httpx~=0.14 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra>=0.5.0->escher) (0.22.0)
    Requirement already satisfied: httpcore<0.15.0,>=0.14.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra>=0.5.0->escher) (0.14.7)
    Requirement already satisfied: rfc3986[idna2008]<2,>=1.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra>=0.5.0->escher) (1.5.0)
    Requirement already satisfied: charset-normalizer in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra>=0.5.0->escher) (2.0.4)
    Requirement already satisfied: certifi in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra>=0.5.0->escher) (2021.10.8)
    Requirement already satisfied: sniffio in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra>=0.5.0->escher) (1.2.0)
    Requirement already satisfied: h11<0.13,>=0.11 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra>=0.5.0->escher) (0.12.0)
    Requirement already satisfied: anyio==3.* in c:\users\merna fathy\anaconda3\lib\site-packages (from httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra>=0.5.0->escher) (3.5.0)
    Requirement already satisfied: idna>=2.8 in c:\users\merna fathy\anaconda3\lib\site-packages (from anyio==3.*->httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra>=0.5.0->escher) (3.2)
    Requirement already satisfied: jupyterlab-widgets>=1.0.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipywidgets<8,>=7.4.0->escher) (1.0.0)
    Requirement already satisfied: ipython>=4.0.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipywidgets<8,>=7.4.0->escher) (7.29.0)
    Requirement already satisfied: traitlets>=4.3.1 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipywidgets<8,>=7.4.0->escher) (5.1.0)
    Requirement already satisfied: nbformat>=4.2.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipywidgets<8,>=7.4.0->escher) (5.1.3)
    Requirement already satisfied: ipykernel>=4.5.1 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipywidgets<8,>=7.4.0->escher) (6.4.1)
    Requirement already satisfied: widgetsnbextension~=3.5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipywidgets<8,>=7.4.0->escher) (3.5.1)
    Requirement already satisfied: ipython-genutils~=0.2.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipywidgets<8,>=7.4.0->escher) (0.2.0)
    Requirement already satisfied: jupyter-client<8.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (6.1.12)
    Requirement already satisfied: matplotlib-inline<0.2.0,>=0.1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (0.1.2)
    Requirement already satisfied: debugpy<2.0,>=1.0.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (1.4.1)
    Requirement already satisfied: tornado<7.0,>=4.2 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (6.1)
    Requirement already satisfied: pickleshare in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (0.7.5)
    Requirement already satisfied: pygments in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (2.10.0)
    Requirement already satisfied: decorator in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (5.1.0)
    Requirement already satisfied: colorama in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (0.4.4)
    Requirement already satisfied: backcall in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (0.2.0)
    Requirement already satisfied: setuptools>=18.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (58.0.4)
    Requirement already satisfied: prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (3.0.20)
    Requirement already satisfied: jedi>=0.16 in c:\users\merna fathy\anaconda3\lib\site-packages (from ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (0.18.0)
    Requirement already satisfied: parso<0.9.0,>=0.8.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from jedi>=0.16->ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (0.8.2)
    Requirement already satisfied: MarkupSafe>=0.23 in c:\users\merna fathy\anaconda3\lib\site-packages (from Jinja2<3,>=2.7.3->escher) (1.1.1)
    Requirement already satisfied: pyrsistent>=0.14.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from jsonschema<4,>=3.0.1->escher) (0.18.0)
    Requirement already satisfied: six>=1.11.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from jsonschema<4,>=3.0.1->escher) (1.16.0)
    Requirement already satisfied: attrs>=17.4.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from jsonschema<4,>=3.0.1->escher) (21.2.0)
    Requirement already satisfied: pyzmq>=13 in c:\users\merna fathy\anaconda3\lib\site-packages (from jupyter-client<8.0->ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (22.2.1)
    Requirement already satisfied: python-dateutil>=2.1 in c:\users\merna fathy\anaconda3\lib\site-packages (from jupyter-client<8.0->ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (2.8.2)
    Requirement already satisfied: jupyter-core>=4.6.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from jupyter-client<8.0->ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (4.8.1)
    Requirement already satisfied: pywin32>=1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from jupyter-core>=4.6.0->jupyter-client<8.0->ipykernel>=4.5.1->ipywidgets<8,>=7.4.0->escher) (228)
    Requirement already satisfied: sympy>=1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from optlang~=1.5->cobra>=0.5.0->escher) (1.9)
    Requirement already satisfied: pytz>=2017.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pandas>=0.18->escher) (2021.3)
    Requirement already satisfied: wcwidth in c:\users\merna fathy\anaconda3\lib\site-packages (from prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0->ipython>=4.0.0->ipywidgets<8,>=7.4.0->escher) (0.2.5)
    Requirement already satisfied: typing-extensions>=3.7.4.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pydantic~=1.6->cobra>=0.5.0->escher) (3.10.0.2)
    Requirement already satisfied: more-itertools>=4.0.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from pytest<5,>=4.0.1->escher) (8.10.0)
    Requirement already satisfied: packaging in c:\users\merna fathy\anaconda3\lib\site-packages (from pytest<5,>=4.0.1->escher) (21.0)
    Requirement already satisfied: pluggy<1.0,>=0.12 in c:\users\merna fathy\anaconda3\lib\site-packages (from pytest<5,>=4.0.1->escher) (0.13.1)
    Requirement already satisfied: py>=1.5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from pytest<5,>=4.0.1->escher) (1.10.0)
    Requirement already satisfied: atomicwrites>=1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from pytest<5,>=4.0.1->escher) (1.4.0)
    Requirement already satisfied: commonmark<0.10.0,>=0.9.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from rich>=8.0->cobra>=0.5.0->escher) (0.9.1)
    Requirement already satisfied: ruamel.yaml.clib>=0.2.6 in c:\users\merna fathy\anaconda3\lib\site-packages (from ruamel.yaml~=0.16->cobra>=0.5.0->escher) (0.2.6)
    Requirement already satisfied: mpmath>=0.19 in c:\users\merna fathy\anaconda3\lib\site-packages (from sympy>=1.0->optlang~=1.5->cobra>=0.5.0->escher) (1.2.1)
    Requirement already satisfied: notebook>=4.4.1 in c:\users\merna fathy\anaconda3\lib\site-packages (from widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (6.4.5)
    Requirement already satisfied: nbconvert in c:\users\merna fathy\anaconda3\lib\site-packages (from notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (6.1.0)
    Requirement already satisfied: prometheus-client in c:\users\merna fathy\anaconda3\lib\site-packages (from notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.11.0)
    Requirement already satisfied: argon2-cffi in c:\users\merna fathy\anaconda3\lib\site-packages (from notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (20.1.0)
    Requirement already satisfied: Send2Trash>=1.5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (1.8.0)
    Requirement already satisfied: terminado>=0.8.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.9.4)
    Requirement already satisfied: pywinpty>=0.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from terminado>=0.8.3->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.5.7)
    Requirement already satisfied: cffi>=1.0.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from argon2-cffi->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (1.14.6)
    Requirement already satisfied: pycparser in c:\users\merna fathy\anaconda3\lib\site-packages (from cffi>=1.0.0->argon2-cffi->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (2.20)
    Requirement already satisfied: zipp>=3.1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from importlib-resources->cobra>=0.5.0->escher) (3.6.0)
    Requirement already satisfied: jupyterlab-pygments in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.1.2)
    Requirement already satisfied: entrypoints>=0.2.2 in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.3)
    Requirement already satisfied: defusedxml in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.7.1)
    Requirement already satisfied: testpath in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.5.0)
    Requirement already satisfied: pandocfilters>=1.4.1 in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (1.4.3)
    Requirement already satisfied: bleach in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (4.0.0)
    Requirement already satisfied: nbclient<0.6.0,>=0.5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.5.3)
    Requirement already satisfied: mistune<2,>=0.8.1 in c:\users\merna fathy\anaconda3\lib\site-packages (from nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.8.4)
    Requirement already satisfied: async-generator in c:\users\merna fathy\anaconda3\lib\site-packages (from nbclient<0.6.0,>=0.5.0->nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (1.10)
    Requirement already satisfied: nest-asyncio in c:\users\merna fathy\anaconda3\lib\site-packages (from nbclient<0.6.0,>=0.5.0->nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (1.5.1)
    Requirement already satisfied: webencodings in c:\users\merna fathy\anaconda3\lib\site-packages (from bleach->nbconvert->notebook>=4.4.1->widgetsnbextension~=3.5.0->ipywidgets<8,>=7.4.0->escher) (0.5.1)
    Requirement already satisfied: pyparsing>=2.0.2 in c:\users\merna fathy\anaconda3\lib\site-packages (from packaging->pytest<5,>=4.0.1->escher) (3.0.4)
    Installing collected packages: pytest, escher
      Attempting uninstall: pytest
        Found existing installation: pytest 6.2.4
        Uninstalling pytest-6.2.4:
          Successfully uninstalled pytest-6.2.4
    Successfully installed escher-1.7.3 pytest-4.6.11
    


```python
import escher
```


```python
from escher import Builder
```


```python
cobra.io.load_json_model("test.json")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_7560/15908374.py in <module>
    ----> 1 cobra.io.load_json_model("test.json")
    

    NameError: name 'cobra' is not defined



```python
builder=Builder()
```


```python
builder
```


    Builder()



```python

```
