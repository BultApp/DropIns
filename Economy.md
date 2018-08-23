# About
Economy addons are supposed to be written in a way to help engage viewers and chatters. They encourage people to become more active and, thus far, have proven to do so. 

# Subscribers
## Required
### Increment Balance
**Topic**: `economy.incrementBalance` 

**Data Object**:
```json
{
  "userId": "",
  "amount": 0
}
```

**Returns**: `number` - New account balance

### Decrement Balance
**Topic**: `economy.derementBalance` 

**Data Object**:
```json
{
  "userId": "",
  "amount": 0
}
```

**Returns**: `number` - New account balance

### Get Balance
**Topic**: `economy.getBalance` 

**Data Object**:
```json
{
  "userId": ""
}
```

**Returns**: `number` - Get the current account balance

### Has Balance
**Topic**: `economy.hasBalance` 

**Data Object**:
```json
{
  "userId": "",
  "amount": 0
}
```

**Returns**: `boolean` - If they have equal or greater then the requested amount
