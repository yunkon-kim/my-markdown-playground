# Alvin's Markdown Playground

## 1. Inner Link
```
[Collapsible code block](#8-Collapsible-code-block)
```
The anchor can work fine **without** the inclusion of the punctuation

[8. Collapsible code block](#8-Collapsible-code-block)

## 2. GitHub Markdown License Badges
See [here](https://gist.github.com/lukas-h/2a5d00690736b4c3a7ba)

## 3. GitHub Markdown Emoji Markup
See [here](https://gist.github.com/rxaviers/7360908)


## 4. Underline
```
<ins>Hello Markdown</ins>
```
<ins>Hello Markdown</ins>


## 5. Line Breaks
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


## 6. Text highlight
Failed :sob:

## 7. Table

### 7.1. Merge cells 

#### 7.1.1. Merge rows (updated on 2020-10-19)

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

#### 7.1.2. Merge columns (updated on 2020-10-19)

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

## 8. Collapsible code block

    <details>
      <summary>Click to expand</summary>
      <p>

      ```bash
      cd ${HOME}
      ```
      </p>
    </details>

<details>
  <summary>Click to expand</summary>
  <p>
  
  ```bash
  cd ${HOME}
  ```
  </p>
</details>
