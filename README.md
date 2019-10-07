#Spark Toast

> Notification dispatch and presentation

## Usage

```javascript
var toast = require('@spark-engine/toast')
```

### `toast(message)`

Uses the 'normal' type of notification.

```javascript
toast('Hello world.')
```

### `toast(type, message)`

Uses the specified type of notification.

```javascript
toast('Hello world.', 'success')
```

### `toast.success`, `toast.error`, `toast.action`, `toast.normal`

Helper functions that do exactly what they say they do.
