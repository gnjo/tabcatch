# tabcatch
tab emulater. gather the div

# usage
```
<div data-tab="g1" data-tabname="edit"></div>
<div data-tab="g1" data-tabname="config"></div>
<div data-tab="g1" data-tabname="usage"></div>

<div data-tab="g2" data-tabname="run"></div>
<div data-tab="g2" data-tabname="help"></div>
<div data-tab="g2" data-tabname="output"></div>
```
```js
 tabcatch('g1')
  .checked('edit')
  .caller(abc)
  .add(element)
  .del(tabname)
```


```
----------------------------------------
| (title)edit | (tool)[short][tab][del]
----------------------------------------
|                                      |
|  (body)                              |
|                                      |
----------------------------------------
```
```
tab(query)
 .add('id','edit','short,tab,del',caller); //caller(type,id,name,obj); //type add,del,click,hide //name edit,short,tab,del 
 .del('id',checkcaller)
 ;
 .gettab() //
 .getkind('id','name') //return 'title','body','tool'
 .get('id','name') //return element
```

