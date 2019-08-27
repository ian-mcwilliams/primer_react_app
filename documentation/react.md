### Generate react code

#### IDE plugin

Get the plugin for your IDE (for WebStorm use "React snippets")

Now in the editor shorthand like "rcc" will offer code completion (for rcc a basic React component is generated)

It works by adding a series of Live Templates - see WebStorm Preferences > Editor > Live Templates > React

#### Zen coding

Generate react html templates using html shorthand followed by tab

```
table.table>thead>tr>th*4
```

```
<table className="table">
  <thead>
    <tr>
      <th>Title</th>
      <th>Genre</th>
      <th>Stock</th>
      <th>Rate</th>
    </tr>
  </thead>
</table>
```
