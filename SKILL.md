# micronaut.data.tx Skill

Use this skill to work with Norm module `micronaut.data.tx` version 2. Use only declarations listed below.

## `micronaut.data.tx`

Source: `Transactional.norm`

### `Transactional`

```norm
annotation Transactional implements TypeTarget, FunctionTarget, RuntimeRetention
```

#### `readOnly`

```norm
Boolean readOnly
```

Type: `Boolean`

#### `transactionManager`

```norm
String transactionManager
```

Type: `String`

#### `Transactional`

```norm
Transactional(Boolean? readOnly, String? transactionManager)
```

Parameters:

- `readOnly`: `Boolean?`
- `transactionManager`: `String?`

