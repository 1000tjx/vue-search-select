# vue-search-select
Easy and simple search select menu

# Demo
![](https://j.gifs.com/jYVnOy.gif)

# Usage

```vue
<VueSearchSelect
  label="name"
  placeholder="Pick a user..."
  :options="[{name: 'Jhon', id: 1}, {name: 'Tareq', id: 2}]"
  no-results-msg='No results for your query'
  @onSelect="(option) => console.log(option)"/>

```
