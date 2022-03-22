```python
!pip install cobra
```

    Requirement already satisfied: cobra in c:\users\merna fathy\anaconda3\lib\site-packages (0.24.0)
    Requirement already satisfied: pydantic~=1.6 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.9.0)
    Requirement already satisfied: rich>=8.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (12.0.0)
    Requirement already satisfied: httpx~=0.14 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (0.22.0)
    Requirement already satisfied: optlang~=1.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.5.2)
    Requirement already satisfied: pandas~=1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.3.4)
    Requirement already satisfied: depinfo~=1.7 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.7.0)
    Requirement already satisfied: swiglpk in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.0.4)
    Requirement already satisfied: numpy~=1.13 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.20.3)
    Requirement already satisfied: appdirs~=1.4 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (1.4.4)
    Requirement already satisfied: python-libsbml==5.19.2 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.19.2)
    Requirement already satisfied: diskcache~=5.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.4.0)
    Requirement already satisfied: ruamel.yaml~=0.16 in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (0.17.21)
    Requirement already satisfied: importlib-resources in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (5.4.0)
    Requirement already satisfied: future in c:\users\merna fathy\anaconda3\lib\site-packages (from cobra) (0.18.2)
    Requirement already satisfied: rfc3986[idna2008]<2,>=1.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (1.5.0)
    Requirement already satisfied: charset-normalizer in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (2.0.4)
    Requirement already satisfied: sniffio in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (1.2.0)
    Requirement already satisfied: httpcore<0.15.0,>=0.14.5 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (0.14.7)
    Requirement already satisfied: certifi in c:\users\merna fathy\anaconda3\lib\site-packages (from httpx~=0.14->cobra) (2021.10.8)
    Requirement already satisfied: h11<0.13,>=0.11 in c:\users\merna fathy\anaconda3\lib\site-packages (from httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra) (0.12.0)
    Requirement already satisfied: anyio==3.* in c:\users\merna fathy\anaconda3\lib\site-packages (from httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra) (3.5.0)
    Requirement already satisfied: idna>=2.8 in c:\users\merna fathy\anaconda3\lib\site-packages (from anyio==3.*->httpcore<0.15.0,>=0.14.5->httpx~=0.14->cobra) (3.2)
    Requirement already satisfied: six>=1.9 in c:\users\merna fathy\anaconda3\lib\site-packages (from optlang~=1.5->cobra) (1.16.0)
    Requirement already satisfied: sympy>=1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from optlang~=1.5->cobra) (1.9)
    Requirement already satisfied: pytz>=2017.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pandas~=1.0->cobra) (2021.3)
    Requirement already satisfied: python-dateutil>=2.7.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pandas~=1.0->cobra) (2.8.2)
    Requirement already satisfied: typing-extensions>=3.7.4.3 in c:\users\merna fathy\anaconda3\lib\site-packages (from pydantic~=1.6->cobra) (3.10.0.2)
    Requirement already satisfied: pygments<3.0.0,>=2.6.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from rich>=8.0->cobra) (2.10.0)
    Requirement already satisfied: commonmark<0.10.0,>=0.9.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from rich>=8.0->cobra) (0.9.1)
    Requirement already satisfied: ruamel.yaml.clib>=0.2.6 in c:\users\merna fathy\anaconda3\lib\site-packages (from ruamel.yaml~=0.16->cobra) (0.2.6)
    Requirement already satisfied: mpmath>=0.19 in c:\users\merna fathy\anaconda3\lib\site-packages (from sympy>=1.0->optlang~=1.5->cobra) (1.2.1)
    Requirement already satisfied: zipp>=3.1.0 in c:\users\merna fathy\anaconda3\lib\site-packages (from importlib-resources->cobra) (3.6.0)
    


```python
import cobra
```


```python
from cobra import Model,Rection,Metabolite
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/709024639.py in <module>
    ----> 1 from cobra import Model,Rection,Metabolite
    

    ImportError: cannot import name 'Rection' from 'cobra' (C:\Users\merna fathy\anaconda3\lib\site-packages\cobra\__init__.py)



```python
model=Model('ex')
```


```python
v1.Reaction('v1')
v1.name='v1'
v1.lower_bound=0
v1.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/2948685302.py in <module>
    ----> 1 v1.Reaction('v1')
          2 v1.name='v1'
          3 v1.lower_bound=0
          4 v1.upper_bound=1000
    

    NameError: name 'v1' is not defined



```python
v2.Reaction('v2')
v2.name='v2'
v2.lower_bound=0
v2.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/3259799772.py in <module>
    ----> 1 v2.Reaction('v2')
          2 v2.name='v2'
          3 v2.lower_bound=0
          4 v2.upper_bound=1000
    

    NameError: name 'v2' is not defined



```python
v0.Reaction('v0')
v0.name='v0'
v0.lower_bound=1
v0.upper_bound=1
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/2815307523.py in <module>
    ----> 1 v0.Reaction('v0')
          2 v0.name='v0'
          3 v0.lower_bound=1
          4 v0.upper_bound=1
    

    NameError: name 'v0' is not defined



```python
M.Reaction('M')
M.name='M'
M.lower_bound=0
M.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/2743851088.py in <module>
    ----> 1 M.Reaction('M')
          2 M.name='M'
          3 M.lower_bound=0
          4 M.upper_bound=1000
    

    NameError: name 'M' is not defined



```python
v3.Reaction('v3')
v3.name='v3'
v3.lower_bound=0
v3.upper_bound=1000
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/860618872.py in <module>
    ----> 1 v3.Reaction('v3')
          2 v3.name='v3'
          3 v3.lower_bound=0
          4 v3.upper_bound=1000
    

    NameError: name 'v3' is not defined



```python
v4.Reaction('v4')
v4.name='v4'
v4.lower_bound=.9
v4.upper_bound=.9
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/1018916764.py in <module>
    ----> 1 v4.Reaction('v4')
          2 v4.name='v4'
          3 v4.lower_bound=.9
          4 v4.upper_bound=.9
    

    NameError: name 'v4' is not defined



```python
A=Metabolite('A',compartment='c')
B=Metabolite('B',compartment='c')
C=Metabolite('C',compartment='c')
ATP=Metabolite('ATP',compartment='c')

```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/2798174544.py in <module>
    ----> 1 A=Metabolite('A',compartment='c')
          2 B=Metabolite('B',compartment='c')
          3 C=Metabolite('C',compartment='c')
          4 ATP=Metabolite('ATP',compartment='c')
    

    NameError: name 'Metabolite' is not defined



```python
v1.add_metabolities({A:-1,B:1})
v2.add_metabolities({B:-1,C:1})
v0.add_metabolities({A:1})
M.add_metabolities({C:-1})
v3.add_metabolities({A:-1,ATP:1})
v4.add_metabolities({ATP:-1})
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/1055880988.py in <module>
    ----> 1 v1.add_metabolities({A:-1,B:1})
          2 v2.add_metabolities({B:-1,C:1})
          3 v0.add_metabolities({A:1})
          4 M.add_metabolities({C:-1})
          5 v3.add_metabolities({A:-1,ATP:1})
    

    NameError: name 'v1' is not defined



```python
model.add_reaction([v1,v2,v0,M,v3,v4])
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/556086919.py in <module>
    ----> 1 model.add_reaction([v1,v2,v0,M,v3,v4])
    

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

    C:\Users\MERNAF~1\AppData\Local\Temp/ipykernel_2328/3062419775.py in <module>
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

```
