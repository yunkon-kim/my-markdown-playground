# Alvin's Markdown Playground

## GitHub Markdown License Badges
See [here](https://gist.github.com/lukas-h/2a5d00690736b4c3a7ba)

## GitHub Markdown Emoji Markup
See [here](https://gist.github.com/rxaviers/7360908)


## Underline
```
<ins>Hello Markdown</ins>
```
<ins>Hello Markdown</ins>


## Line Breaks
```
Hello  <!--Double space-->
Markdown
```
Hello  
Markdown   

```
Hello<br>
Markdown
```
Hello<br>
Markdown


## Text highlight
Failed :sob:

## Table

### Merge cells 

#### Merge rows (updated on 2020-10-19)

```html
<table>
<thead>
  <tr class="header">
    <th><strong> Header 1 </strong></th>
    <th><strong> Header 2 </strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2"><p><strong>A</strong></p></td>
    <td><p>B</p></td>
  </tr>
  <tr>
    <!-- merged td -->
    <td><p>C</p></td>
  </tr>  
  </tbody>
</table>
```

<table>
<thead>
  <tr class="header">
    <th><strong> Header 1 </strong></th>
    <th><strong> Header 2 </strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2"><p><strong>A</strong></p></td>
    <td><p>B</p></td>
  </tr>
  <tr>
    <!-- merged td -->
    <td><p>C</p></td>
  </tr>  
  </tbody>
</table>

#### Merge columns (updated on 2020-10-19)

```html
<table>
<thead>
  <tr class="header">
    <th><strong> Header 1 </strong></th>
    <th><strong> Header 2 </strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2"><p><strong>A</strong></p></td>
    <!-- merged td -->
  </tr>
  <tr>
    <td><p>C</p></td>
    <td><p>D</p></td>
  </tr>  
  </tbody>
</table>
```

<table>
<thead>
  <tr class="header">
    <th><strong> Header 1 </strong></th>
    <th><strong> Header 2 </strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2"><p><strong>A</strong></p></td>
    <!-- merged td -->
  </tr>
  <tr>
    <td><p>C</p></td>
    <td><p>D</p></td>
  </tr>  
  </tbody>
</table>
