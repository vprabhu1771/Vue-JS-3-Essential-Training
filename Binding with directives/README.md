# Binding with directives

# Regular HTML

```
<img src="image.png" alt="some image">
```

# Mustaches `{{imgSrc}}` don't work

```
<img src="{{imgSrc}}" alt="some image">
```

# Using Directives


```
<img v-bind:src="imgSrc" alt="some image">
```

OR

```
<img v-bind:src="imgSrc" v-bind:alt="name">
```

The `v-bind:id="expression"` directive

The `:id="expression"` directive

The `:src="expression"` directive

The `:src="myVar"` directive

Shortcut to `v-bind`

```
<img :src="myVariable" alt="some image">
```

`v-bind` is part of a family of commands called directives

- Attribute with `v-` prefix
- Take arguments (`v-bind`)
- Single JavaScript expressions
- Reactive Binding