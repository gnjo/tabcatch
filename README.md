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


```js
{
name:'edit'
,id:'xyz'
,group:'g1'
,on:{
 init:(e)=>{}
 ,open:(e)=>{}
 ,close:(e)=>{}
}
,cmd:{
 short:(e)=>{}
 ,tab:(e)=>{}
}
}
```
```
--------------------------------------
| edit |                  [short][tab]
--------------------------------------
|                                    |
|                                    |
|                                    |
--------------------------------------
```
