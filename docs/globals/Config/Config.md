import Tabs from '@theme/Tabs'
import TabItem from '@theme/TabItem'

A global API used to save and load avatar data between game sessions

:::warning
This page is a WIP. It contains all the information in Figura's documentation but we're working on adding more helpful descriptions.
:::

---

### <code>setName()</code> \{#setName}

**Aliases:** `name()`

Sets the name of the destination file, data will be saved and loaded from that file

Defaults to the avatar name

```lua
setName(name)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| name | <code>[String](/tutorials/types/Strings)</code> | -           | -       |

**Returns:**

| Type                                      | Description               |
| ----------------------------------------- | ------------------------- |
| <code>[ConfigAPI](/globals/Config)</code> | Returns self for chaining |

**Example:**

```lua
config:setName("Something")
```

---

### <code>getName()</code> \{#getName}

Returns the name of the destination file

```lua
getName()
```

**Returns:**

| Type                                            | Description |
| ----------------------------------------------- | ----------- |
| <code>[String](/tutorials/types/Strings)</code> | -           |

**Example:**

```lua
config:getName()
```

---

### <code>load()</code> \{#load}

Loads a saved variable under the specific key

If no key is given, it will return a table with all saved variables

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
load()
```

**Returns:**

| Type                                          | Description |
| --------------------------------------------- | ----------- |
| <code>[Table](/tutorials/types/Tables)</code> | -           |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
load(key)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| key  | <code>[String](/tutorials/types/Strings)</code> | -           | -       |

**Returns:**

| Type                 | Description |
| -------------------- | ----------- |
| <code>AnyType</code> | -           |

</TabItem>
</Tabs>

**Example:**

```lua
config:load("apple")
```

---

### <code>save()</code> \{#save}

Save to disk a variable under the specific key

If the value is nil, the variable is removed from the file

```lua
save(key, value)
```

**Parameters:**

| Name  | Type                                            | Description | Default |
| ----- | ----------------------------------------------- | ----------- | ------- |
| key   | <code>[String](/tutorials/types/Strings)</code> | -           | -       |
| value | <code>AnyType</code>                            | -           | -       |

**Returns:**

| Type                                      | Description               |
| ----------------------------------------- | ------------------------- |
| <code>[ConfigAPI](/globals/Config)</code> | Returns self for chaining |

**Example:**

```lua
config:save("apple", false)
```

---
