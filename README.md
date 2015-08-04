# craft-fork

Parameterized fork model.

### Usage
```html
<craft>
    <craft name="fork" module="craft-fork"/>
    <fork></fork>
</craft>
```

### Parameters
- length: adjusts length of fork
- spork: adjusts between fork and spork
    - 0 = fork
    - 1 = spork

### Example
```html
<craft>
    <craft name="fork" module="craft-fork"/>
    <row spacing="2">
        <fork length="15" t="scale(2 2 2)"></fork>
        <fork length="20" spork="1"></fork>
        <fork></fork>
    </row>
</craft>
```

![example](example.png)