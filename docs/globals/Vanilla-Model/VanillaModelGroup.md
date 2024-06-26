import Tabs from '@theme/Tabs'
import TabItem from '@theme/TabItem'

Represents a group of model parts in a vanilla model

:::warning
This page is a WIP. It contains all the information in Figura's documentation but we're working on adding more helpful descriptions.
:::

Used for easy reference of normal parts

All changes also applies to all children parts

---

### <code>setOffsetRot()</code> \{#setOffsetRot}

**Aliases:** `offsetRot()`

Offsets this part and its children's rotation, adding on top of the vanilla values

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
setOffsetRot(offsetRot)
```

**Parameters:**

| Name      | Type                                             | Description | Default |
| --------- | ------------------------------------------------ | ----------- | ------- |
| offsetRot | <code>[Vector3](/globals/Vectors/Vector3)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
setOffsetRot(x, y, z)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| x    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| y    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| z    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
</Tabs>

**Example:**

```lua
vanilla_model.ALL:setOffsetRot(0, 90, 0)
```

---

### <code>getOffsetRot()</code> \{#getOffsetRot}

Gets this part's rotation offset

```lua
getOffsetRot()
```

**Returns:**

| Type                                             | Description |
| ------------------------------------------------ | ----------- |
| <code>[Vector3](/globals/Vectors/Vector3)</code> | -           |

**Example:**

```lua
vanilla_model.ALL:getOffsetRot()
```

---

### <code>setOffsetScale()</code> \{#setOffsetScale}

**Aliases:** `offsetScale()`

Offsets this part and its children's scale, multiplying with the vanilla values

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
setOffsetScale(offsetScale)
```

**Parameters:**

| Name        | Type                                             | Description | Default |
| ----------- | ------------------------------------------------ | ----------- | ------- |
| offsetScale | <code>[Vector3](/globals/Vectors/Vector3)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
setOffsetScale(x, y, z)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| x    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| y    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| z    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
</Tabs>

**Example:**

```lua
vanilla_model.ALL:setOffsetScale(2, 2, 2)
```

---

### <code>getOffsetScale()</code> \{#getOffsetScale}

Gets this part's scale offset

```lua
getOffsetScale()
```

**Returns:**

| Type                                             | Description |
| ------------------------------------------------ | ----------- |
| <code>[Vector3](/globals/Vectors/Vector3)</code> | -           |

**Example:**

```lua
vanilla_model.ALL:getOffsetScale()
```

---

### <code>setPos()</code> \{#setPos}

**Aliases:** `pos()`

Set this part and its children's position, preserving the previous values

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
setPos(pos)
```

**Parameters:**

| Name | Type                                             | Description | Default |
| ---- | ------------------------------------------------ | ----------- | ------- |
| pos  | <code>[Vector3](/globals/Vectors/Vector3)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
setPos(x, y, z)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| x    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| y    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| z    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
</Tabs>

**Example:**

```lua
vanilla_model.ALL:setPos(0, 10, 0)
```

---

### <code>getPos()</code> \{#getPos}

Get this part's set position

Returns the value set by the "set" function

```lua
getPos()
```

**Returns:**

| Type                                             | Description |
| ------------------------------------------------ | ----------- |
| <code>[Vector3](/globals/Vectors/Vector3)</code> | -           |

**Example:**

```lua
vanilla_model.ALL:getPos()
```

---

### <code>setRot()</code> \{#setRot}

**Aliases:** `rot()`

Set this part and its children's rotation

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
setRot(rot)
```

**Parameters:**

| Name | Type                                             | Description | Default |
| ---- | ------------------------------------------------ | ----------- | ------- |
| rot  | <code>[Vector3](/globals/Vectors/Vector3)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
setRot(x, y, z)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| x    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| y    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| z    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
</Tabs>

**Example:**

```lua
vanilla_model.ALL:setRot(0, 90, 0)
```

---

### <code>getRot()</code> \{#getRot}

Get this part's set rotation

Returns the value set by the "set" function

```lua
getRot()
```

**Returns:**

| Type                                             | Description |
| ------------------------------------------------ | ----------- |
| <code>[Vector3](/globals/Vectors/Vector3)</code> | -           |

**Example:**

```lua
vanilla_model.ALL:getRot()
```

---

### <code>setScale()</code> \{#setScale}

**Aliases:** `scale()`

Set this part and its children's scale

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
setScale(scale)
```

**Parameters:**

| Name  | Type                                             | Description | Default |
| ----- | ------------------------------------------------ | ----------- | ------- |
| scale | <code>[Vector3](/globals/Vectors/Vector3)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
setScale(x, y, z)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| x    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| y    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |
| z    | <code>[Number](/tutorials/types/Numbers)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

</TabItem>
</Tabs>

**Example:**

```lua
vanilla_model.ALL:setScale(2, 2, 2)
```

---

### <code>getScale()</code> \{#getScale}

Get this part's set scale

Returns the value set by the "set" function

```lua
getScale()
```

**Returns:**

| Type                                             | Description |
| ------------------------------------------------ | ----------- |
| <code>[Vector3](/globals/Vectors/Vector3)</code> | -           |

**Example:**

```lua
vanilla_model.ALL:getScale()
```

---

### <code>setVisible()</code> \{#setVisible}

**Aliases:** `visible()`

Sets this part and its children to be visible or invisible

```lua
setVisible(visible)
```

**Parameters:**

| Name    | Type                                              | Description | Default |
| ------- | ------------------------------------------------- | ----------- | ------- |
| visible | <code>[Boolean](/tutorials/types/Booleans)</code> | -           | -       |

**Returns:**

| Type                                                           | Description |
| -------------------------------------------------------------- | ----------- |
| <code>[VanillaPart](/globals/Vanilla-Model/VanillaPart)</code> | -           |

**Example:**

```lua
vanilla_model.ALL:setVisible(false)
```

---

### <code>getVisible()</code> \{#getVisible}

Gets whether you have set this part to be visible or invisible

```lua
getVisible()
```

**Returns:**

| Type                                              | Description |
| ------------------------------------------------- | ----------- |
| <code>[Boolean](/tutorials/types/Booleans)</code> | -           |

**Example:**

```lua
vanilla_model.ALL:getVisible()
```

---
