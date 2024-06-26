import Tabs from '@theme/Tabs'
import TabItem from '@theme/TabItem'

A builder for HTTP request

:::warning
This page is a WIP. It contains all the information in Figura's documentation but we're working on adding more helpful descriptions.
:::

---

### <code>getBody()</code> \{#getBody}

Returns body of this request

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
getBody()
```

**Returns:**

| Type                                                  | Description |
| ----------------------------------------------------- | ----------- |
| <code>[InputStream](/globals/Data/InputStream)</code> | -           |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
getBody()
```

**Returns:**

| Type                                        | Description |
| ------------------------------------------- | ----------- |
| <code>[Buffer](/globals/Data/Buffer)</code> | -           |

</TabItem>
</Tabs>

**Example:**

```lua
-- example coming soon
```

---

### <code>getHeaders()</code> \{#getHeaders}

Returns table with all headers set for this request

```lua
getHeaders()
```

**Returns:**

| Type                                          | Description |
| --------------------------------------------- | ----------- |
| <code>[Table](/tutorials/types/Tables)</code> | -           |

**Example:**

```lua
-- example coming soon
```

---

### <code>getMethod()</code> \{#getMethod}

Returns method of this request

```lua
getMethod()
```

**Returns:**

| Type                                            | Description |
| ----------------------------------------------- | ----------- |
| <code>[String](/tutorials/types/Strings)</code> | -           |

**Example:**

```lua
-- example coming soon
```

---

### <code>getUri()</code> \{#getUri}

Returns URI of this request

```lua
getUri()
```

**Returns:**

| Type                                            | Description |
| ----------------------------------------------- | ----------- |
| <code>[String](/tutorials/types/Strings)</code> | -           |

**Example:**

```lua
-- example coming soon
```

---

### <code>body()</code> \{#body}

Sets body for this request, returns itself for chaining. If data is nil request will be sent without body

<Tabs>
<TabItem value="overload-1" label="Overload 1">

```lua
body(data)
```

**Parameters:**

| Name | Type                                                  | Description | Default |
| ---- | ----------------------------------------------------- | ----------- | ------- |
| data | <code>[InputStream](/globals/Data/InputStream)</code> | -           | -       |

**Returns:**

| Type                                                               | Description               |
| ------------------------------------------------------------------ | ------------------------- |
| <code>[HttpRequestBuilder](/globals/Net/HttpRequestBuilder)</code> | Returns self for chaining |

</TabItem>
<TabItem value="overload-2" label="Overload 2">

```lua
body(data)
```

**Parameters:**

| Name | Type                                        | Description | Default |
| ---- | ------------------------------------------- | ----------- | ------- |
| data | <code>[Buffer](/globals/Data/Buffer)</code> | -           | -       |

**Returns:**

| Type                                                               | Description               |
| ------------------------------------------------------------------ | ------------------------- |
| <code>[HttpRequestBuilder](/globals/Net/HttpRequestBuilder)</code> | Returns self for chaining |

</TabItem>
</Tabs>

**Example:**

```lua
-- example coming soon
```

---

### <code>header()</code> \{#header}

Sets header for this request, returns itself for chaining. If value is nil header will be removed

```lua
header(header, value)
```

**Parameters:**

| Name   | Type                                            | Description | Default |
| ------ | ----------------------------------------------- | ----------- | ------- |
| header | <code>[String](/tutorials/types/Strings)</code> | -           | -       |
| value  | <code>[String](/tutorials/types/Strings)</code> | -           | -       |

**Returns:**

| Type                                                               | Description               |
| ------------------------------------------------------------------ | ------------------------- |
| <code>[HttpRequestBuilder](/globals/Net/HttpRequestBuilder)</code> | Returns self for chaining |

**Example:**

```lua
-- example coming soon
```

---

### <code>method()</code> \{#method}

Sets method for this request, returns itself for chaining. If method is nil default value - "GET", will be used

```lua
method(method)
```

**Parameters:**

| Name   | Type                                            | Description | Default |
| ------ | ----------------------------------------------- | ----------- | ------- |
| method | <code>[String](/tutorials/types/Strings)</code> | -           | -       |

**Returns:**

| Type                                                               | Description               |
| ------------------------------------------------------------------ | ------------------------- |
| <code>[HttpRequestBuilder](/globals/Net/HttpRequestBuilder)</code> | Returns self for chaining |

**Example:**

```lua
-- example coming soon
```

---

### <code>send()</code> \{#send}

Sends this request and returns Future object that will contain response object once request is done

```lua
send()
```

**Returns:**

| Type                                        | Description |
| ------------------------------------------- | ----------- |
| <code>[Future](/globals/Data/Future)</code> | -           |

**Example:**

```lua
-- example coming soon
```

---

### <code>uri()</code> \{#uri}

Sets URI for this request, returns itself for chaining

```lua
uri(uri)
```

**Parameters:**

| Name | Type                                            | Description | Default |
| ---- | ----------------------------------------------- | ----------- | ------- |
| uri  | <code>[String](/tutorials/types/Strings)</code> | -           | -       |

**Returns:**

| Type                                                               | Description               |
| ------------------------------------------------------------------ | ------------------------- |
| <code>[HttpRequestBuilder](/globals/Net/HttpRequestBuilder)</code> | Returns self for chaining |

**Example:**

```lua
-- example coming soon
```

---
